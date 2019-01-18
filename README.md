# Hobo Breakable
> GameMaker extension for adding breakable object functionality with a few scripts
> * 2 scripts turn any object into a breakable one
> * Easy usage
> * Switching gravity on or off is a boolean away.
> * Implementation open ended; allows for full customization.

![](https://marketplacecdn.yoyogames.com/images/assets/962/screenshots/2606_original.png?1413938292)


## How to Use
1. Import the extension into GM
2. Open the extension and `Import All` resources
3. Add the following to any object you want to become "breakable"

```
//initialize breakable object (typically in create)
break_id = init_breakable(1);
//break the object (typically replaces old destroy action)
destroy(break_id, o_player);
//treat objects with physics (option that can be set on gamestart if needed)
global.phy_set = true;
```


**Version Log**

* **v 0.0.3:**

1. Fix offset bug

* **v 0.02:**

1. Code Cleanup
2. Add gravity control global (**global.phy_set**)
3. 1/2 fix offset bug    

* **v 0.01:**

1. Booze drank
2. Scripts produced
3. Buggy alpha