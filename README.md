##  A simple counter of player on a minecraft server 

Displays the number of online players in your Minecraft Server on your website using 2 lines of HTML.

The only two lines needed are the script tag and the element that will display the number. Example:

```html

<script src="https://lounge-lizard-dev.github.io/minecraft-counter-server/script.js"></script>

There are <span data-playercounter-ip="mc.hypixel.net">0</span> players on Hypixel right now.

```

### Options

### Example (including HTML template):

#### HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- ... -->
    <script src="https://lounge-lizard-dev.github.io/minecraft-counter-server/script.js"></script>
  </head>
  <body>
    There are <span data-playercounter-ip="my.server.ip">0</span> players online on my server.
  </body>
</html>
```
#### JS ("API")
```js
new PlayerCounter({
  element: element,
  ip: 'server ip',
  format: '{online}/{max}' // default {online}
  refreshRate: 60 * 1000 // default 1m
});
```
### Lisence

Copyright (C) 2021  Lounge Lizard dev contactlounge.dev@gmail.com
Licensed under the MIT License. See LICENSE file in the project root for full license information.
