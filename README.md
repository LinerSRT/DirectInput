# DirectInput

This project can help you to deal with DirectInput in Java. 

If you need send key events or mouse events to an windows application\game and java.awt.Robot doesn't work, you can try this


Here a quick example:

```java
public class DirectUnputTest {
  public static void main(String[] args) {
        DirectInput.pressKey(KeyEvent.VK_W); // Press W key
        DirectInput.releaseKey(KeyEvent.VK_W); // Release W key
        DirectInput.mouseMove(100, 100); // Move mouse to x, y
        DirectInput.mouseLeftClick(100, 100); // Mouse left click at x, y
        DirectInput.mouseMiddleClick(100, 100); // Mouse middle click at x, y
        DirectInput.mouseRightClick(100, 100); // Mouse right click at x, y
    }
}

```
