# AsyncAPI Hub

## Customizing it

### Customizable UI areas

|Area|Type|Description|
|---|---|---|
| Topbar > Not logged in | React Component | The area on the right side of the top bar. Only when user is not signed in.
| User Menu | JSON | Add new items to the menu.
| Settings > Organization > Sidebar Menu | JSON | Add new items to the menu.
| Settings > Organization > Custom Page | Page | Where the Sidebar Menu item points to.
| Waiting List Page | Page | The waiting list page.

### Customizable server areas

|Area|Type|Description|
|---|---|---|
| Routes | JS Object | Add new routes to the server.

### Server hooks

|Hook|Description|
|---|---|
| `auth:github` | Triggered when user signs in using Github.
| `server:middlewares` | Attach your plugin middlewares to the Express server pipeline.
| `server:routes` | Attach your own plugin routes to the Express server.
