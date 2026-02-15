## 🚀 On Load Animation

When the app starts, all login elements smoothly appear with a fade + slide effect.

### 🎬 Animation Effect

- Fade In (0 → 100% opacity)
- Slide Up from bottom
- Smooth 800ms duration
- Modern clean startup feel

---

## 📂 Animation File

### 📁 res/anim/on_load.xml

```xml
<?xml version="1.0" encoding="utf-8"?>
<set xmlns:android="http://schemas.android.com/apk/res/android"
    android:interpolator="@android:anim/decelerate_interpolator">

    <alpha
        android:fromAlpha="0.0"
        android:toAlpha="1.0"
        android:duration="800" />

    <translate
        android:fromYDelta="50%"
        android:toYDelta="0%"
        android:duration="800" />

</set>
