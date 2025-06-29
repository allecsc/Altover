<h1 align="center">Altover</h1>

<div align="center">
    <a href="https://zen-browser.app/">
        <img width="120" alt="zen-badge-dark" src="https://github.com/user-attachments/assets/d6ab3ddf-6630-4062-92d0-22497d2a3f9a" />
    </a>
</div>
<h4 align="center">•inspired by the best of the Zen community•</h4>

https://github.com/user-attachments/assets/aeb14a5f-7cab-4a0f-bbbf-f679bf772d93

<h2 align="left">👀 What is Altover?</h2>

###

Altover is a refined fusion of Zen themes—rooted in [Nebula](https://github.com/JustAdumbPrsn/Zen-Nebula), inspired by [Natsumi](https://github.com/greeeen-dev/natsumi-browser), [Zemini](https://github.com/Mohammed55Z/Zemini), and [ZenZero](https://github.com/sameerasw/ZenZero), and shaped with a personal edge. It takes glassmorphism further, blending sharp minimal lines with soft blur and subtle golden highlights for a sleek, elevated UI experience.

###


## ✨ Features

- Add-On for Nebula theme. _Check the store for [Standalone](https://github.com/allecsc/Altover/tree/standalone) version_
- Glass aesthetic with accent highlights _(Best used with dark theme)_
- Floating panels with smooth transitions
- Seamless, minimal UI elements
- Glowing animations
- Clean and simplified container styles
---

## 💫 Sine Setup & Altover Installation (Recommended)

To get Altover working correctly, follow the steps below. This setup builds on **Sine**, uses the **Nebula** theme as a base, and layers on custom styling for a refined, glassy aesthetic.

---

### 1. 📝 Install Sine

* Visit [Sine on GitHub](https://github.com/CosmoCreeper/Sine/tree/main) and follow the installation instructions.
* This includes setting up **FX-Autoconfig** via the auto-installer or manually.
* Once installed, Sine will be accessible in Zen Browser’s settings.

---

### 2. 💎 Install the Altover + Nebula Bundle

#### Option A: *Via Sine Marketplace* (Recommended)

* Open Zen Browser settings → **Sine**
* Launch the **Marketplace**
* Find **Altover** and click **Install**. This will install **BOTH** _Altover_ and _Nebula_ at the same time.

![image](https://github.com/user-attachments/assets/a6a88c52-011f-46aa-b4be-1f8fd147ac8c)

#### Option B: *Manual Installation*

* Follow the instructions from the [Nebula GitHub repo](https://github.com/JustAdumbPrsn/Zen-Nebula)
* Download the latest [Altover.zip](https://github.com/allecsc/Altover/releases).
* Use the `userChrome.css` file provided in the ZIP and paste it directly into your `chrome` folder.

  **OR**

* Open your `userChrome.css` and add:
     ```css
     @import "Altover/Nebula_override.css";
     @import "Altover/Altover.css";
     ```
---

### 3. 🧊 Enable Transparency

To achieve the full glassmorphism effect:

* **Zen Zero** – Adds core transparency and animation support
  → [Download here](https://www.sameerasw.com/zen)

* **DWMBlurGlass** – For system-level blur (Windows 10/11)
  → [Download here](https://github.com/Maplespe/DWMBlurGlass)

  *or*

* **Mica For Everyone** – *Alternative for Windows 11 only*
  → [GitHub](https://github.com/MicaForEveryone/MicaForEveryone)

---

## 🔧 Recommended Add-ons (via Sine)

To enhance the experience further, install these Sine-compatible mods:

* **SuperPins** – Improves pinned tab behavior and visuals
* **Icon Tweaker** – Resize tab icons for Essentials, Pinned, and Workspace indicators

---

## 🪟 Optional: Windows 11 Taskbar Styling (Windhawk)

Take Altover beyond the browser by matching your system taskbar to its style.


![taskbar](https://github.com/user-attachments/assets/ed59c799-0107-4484-aba6-2a9541c2cd56)


### Installation Instructions

1. **Download Windhawk**
   - Visit [https://windhawk.net](https://windhawk.net) and install the Windhawk runtime.
   - Follow the prompts to allow modifications.

2. **Install Required Mods**
   - Install these mods from the Windhawk interface:
     - ✅ **Windows 11 Taskbar Styler**
     - ✅ **Taskbar height and icon size**
       
   - Optional:
     - ✅ **Taskbar Clock Customization** *(only if using the style without clock)*
     - ✅ **Taskbar auto-hide when maximized** *(for improved hiding behavior)*
     - ✅ **Better Taskbar Autohide** *(for improved hiding behavior)*

3. **Taskbar height and icon size**
   - Click on *Details*.
   - Go to **Advanced** and paste this into *Mod settings*:

     ```json
     {"IconSize": "30", "TaskbarHeight": "58","TaskbarButtonWidth": "44"}
     ```
4. **Windows 11 Taskbar Styler**
   - Click on *Details*.
   - Go to **Advanced** and paste one of the **Config Variants** below into *Mod settings*.
   - Optional: *Enable **Auto-hide taskbar when maximized** and pair with **Better Taskbar Autohide** for cleaner behavior.*
     
### Config Variants

1. **Clock visible**
  
   ![clock](https://github.com/user-attachments/assets/ade75433-7296-4f44-8519-ffb4f75e87e3)

   ```json
    {"theme":"DockLike","styleConstants[0]":"","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[0].target":"Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel","controlStyles[0].styles[0]":"Padding=0,0,0,0","controlStyles[1].target":"Grid#SystemTrayFrameGrid","controlStyles[1].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#AARRGGBB\" />","controlStyles[2].target":"Taskbar.AugmentedEntryPointButton > Taskbar.TaskListButtonPanel","controlStyles[2].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#AARRGGBB\" />","controlStyles[1].styles[1]":"CornerRadius=15","controlStyles[3].target":"Taskbar.TaskbarFrame > Grid#RootGrid","controlStyles[3].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#AARRGGBB\" />","controlStyles[3].styles[1]":"CornerRadius=20","controlStyles[1].styles[2]":"Margin=8,1,127,3","controlStyles[1].styles[3]":"BorderThickness=5,1,5,1","controlStyles[1].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[3].styles[2]":"BorderThickness=5,1,5,1","controlStyles[4].target":"Taskbar.TaskbarFrame#TaskbarFrame","controlStyles[4].styles[0]":"Transform3D:=<CompositeTransform3D TranslateX= \"0\"/>","controlStyles[3].styles[3]":"BorderBrush:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","controlStyles[1].styles[5]":"BorderBrush:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","controlStyles[3].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[3].styles[5]":"Margin=0,1,0,3","controlStyles[3].styles[6]":"Padding=-145,1,12,-2","controlStyles[5].target":"Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator","controlStyles[5].styles[0]":"Height=44","controlStyles[5].styles[1]":"RadiusX=5","controlStyles[5].styles[2]":"RadiusY=5","controlStyles[5].styles[3]":"StrokeThickness=1.3","controlStyles[5].styles[4]":"Stroke@InactivePointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[5].styles[5]":"Stroke@InactivePressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[5].styles[6]":"Stroke@ActiveNormal:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#f38518\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","controlStyles[5].styles[7]":"Stroke@ActivePointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[5].styles[8]":"Stroke@ActivePressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[5].styles[9]":"Stroke@InactiveNormal:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"{ThemeResource SystemAccentColorLight2}\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","controlStyles[5].styles[10]":"Fill:=Transparent","controlStyles[5].styles[11]":"Width=40","controlStyles[5].styles[12]":"Visibility=Visible","controlStyles[7].target":"SystemTray.ChevronIconView","controlStyles[7].styles[0]":"Opacity=0","controlStyles[8].target":"SystemTray.NotifyIconView#NotifyItemIcon","controlStyles[8].styles[0]":"Padding=0","controlStyles[9].target":"SystemTray.OmniButton","controlStyles[9].styles[0]":"Padding=0","controlStyles[10].target":"SystemTray.Stack#ShowDesktopStack","controlStyles[10].styles[0]":"Margin=0,4,10,4","controlStyles[6].target":"SystemTray.TextIconContent > Grid#ContainerGrid > SystemTray.AdaptiveTextBlock#Base > TextBlock#InnerTextBlock","controlStyles[6].styles[0]":"FontSize=20","controlStyles[11].target":"SystemTray.ImageIconContent > Grid#ContainerGrid > Image","controlStyles[11].styles[0]":"Width=20","controlStyles[11].styles[1]":"Height=20","controlStyles[1].styles[6]":"Padding=-20,0,-10,0","controlStyles[1].styles[7]":"MaxHeight=30"}
    ```
2. **No clock**
   - Requires **Taskbar Clock Customization** -> Hide *Top line style* and *Bottom line style* from **Settings**

    ![no_clock](https://github.com/user-attachments/assets/f7a4f081-42dd-4b6d-b35d-564517e5ba66)

   ```json
    {"theme":"DockLike","styleConstants[0]":"","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[0].target":"Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel","controlStyles[0].styles[0]":"Padding=0,0,0,0","controlStyles[1].target":"Grid#SystemTrayFrameGrid","controlStyles[1].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#AARRGGBB\" />","controlStyles[2].target":"Taskbar.AugmentedEntryPointButton > Taskbar.TaskListButtonPanel","controlStyles[2].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#AARRGGBB\" />","controlStyles[1].styles[1]":"CornerRadius=15","controlStyles[3].target":"Taskbar.TaskbarFrame > Grid#RootGrid","controlStyles[3].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#AARRGGBB\" />","controlStyles[3].styles[1]":"CornerRadius=20","controlStyles[1].styles[2]":"Margin=8,1,127,3","controlStyles[1].styles[3]":"BorderThickness=5,1,5,1","controlStyles[1].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[3].styles[2]":"BorderThickness=5,1,5,1","controlStyles[4].target":"Taskbar.TaskbarFrame#TaskbarFrame","controlStyles[4].styles[0]":"Transform3D:=<CompositeTransform3D TranslateX= \"0\"/>","controlStyles[3].styles[3]":"BorderBrush:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","controlStyles[1].styles[5]":"BorderBrush:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","controlStyles[3].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[3].styles[5]":"Margin=0,1,0,3","controlStyles[3].styles[6]":"Padding=-145,1,12,-2","controlStyles[5].target":"Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator","controlStyles[5].styles[0]":"Height=44","controlStyles[5].styles[1]":"RadiusX=5","controlStyles[5].styles[2]":"RadiusY=5","controlStyles[5].styles[3]":"StrokeThickness=1.3","controlStyles[5].styles[4]":"Stroke@InactivePointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[5].styles[5]":"Stroke@InactivePressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[5].styles[6]":"Stroke@ActiveNormal:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#f38518\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","controlStyles[5].styles[7]":"Stroke@ActivePointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[5].styles[8]":"Stroke@ActivePressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[5].styles[9]":"Stroke@InactiveNormal:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"{ThemeResource SystemAccentColorLight2}\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","controlStyles[5].styles[10]":"Fill:=Transparent","controlStyles[5].styles[11]":"Width=40","controlStyles[5].styles[12]":"Visibility=Visible","controlStyles[7].target":"SystemTray.ChevronIconView","controlStyles[7].styles[0]":"Opacity=0","controlStyles[8].target":"SystemTray.NotifyIconView#NotifyItemIcon","controlStyles[8].styles[0]":"Padding=0","controlStyles[9].target":"SystemTray.OmniButton","controlStyles[9].styles[0]":"Padding=0","controlStyles[10].target":"SystemTray.Stack#ShowDesktopStack","controlStyles[10].styles[0]":"Margin=0,4,10,4","controlStyles[6].target":"SystemTray.TextIconContent > Grid#ContainerGrid > SystemTray.AdaptiveTextBlock#Base > TextBlock#InnerTextBlock","controlStyles[6].styles[0]":"FontSize=20","controlStyles[11].target":"SystemTray.ImageIconContent > Grid#ContainerGrid > Image","controlStyles[11].styles[0]":"Width=20","controlStyles[11].styles[1]":"Height=20","controlStyles[1].styles[6]":"Padding=-20,0,-30,0","controlStyles[1].styles[7]":"MaxHeight=30"}
    ```

---

## 📣 Feedback / Contributions

This is a personal project and not actively maintained for public feature requests, but if you find issues or want to share improvements, feel free to open an issue or fork the project.
