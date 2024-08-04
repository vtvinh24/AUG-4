### Introduction

## Name
## Image
## Badges
## Description
The idea: a web app similar to Reddit, which users can create own space (sub-reddit). For the implementation:
- **Root**: The main server. This does not store users data except for login credentials (if they choose to use), as well as provide hosting solutions.
- **Node**: The nodes. Users can deploy their own servers to connect with the **Root**, choose to use main features or implement their own.
- **Leaf**: The client (for example a web app). Users (more precisely: Users' users) will use the **Leaf** to connect with the network of servers.

Features that must be implemented:
- Decentralized data storage: each **Node** stores and manages its own data, except for any that opted to use the default solution provided by **Root**
- Each **Node** must at least register with the **Root** (to use provided features such as single login endpoint, however this idea is not completed)
- By default, the **Leaf** supports all **Root** features and **Node**'s default feature.
- Modules system: **Node** and **Leaf** can use modules/plugins/expansions. And they can be created by **Node** owners, I will need to create an API or something.

Features that should be implemented:
- Multiple alternatives for: auth, database engine, ... (anything that has alternatives)
- Safety: this idea is also not completed

...
