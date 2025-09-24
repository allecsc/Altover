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

_This version works as an add-on for Nebula._

<h3 align="center" style="font-size: 1.8em; font-weight: bold; color: #da8d5e;">
 • • • <a href="https://github.com/allecsc/Altover/tree/standalone" style="color: #da8d5e; text-decoration: none;">Check out the <u>Standalone</u> version</a> • • •
</h3>
    
###


## ✨ Features

- Add-On for Nebula theme.
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
### **NEW VERSION**
* **Windows 11 Taskbar Styler**
   ```json
    {"theme":"DockLike","styleConstants[0]":"blurBackground = <WindhawkBlur BlurAmount=\"3\" TintColor=\"#88000000\" />","styleConstants[1]":"mainCornerRadius = 15","styleConstants[2]":"taskbarCornerRadius = 20","styleConstants[3]":"accentGradient = <LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#f38518\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","styleConstants[4]":"borderGradient = <LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","styleConstants[5]":"overlayColor = <SolidColorBrush Color=\"{ThemeResource SystemBaseHighColor}\" Opacity=\"0.3\" />","styleConstants[6]":"inverseBWColor = <SolidColorBrush Color=\"{ThemeResource SystemBaseHighColor}\" Opacity=\"1\" />","styleConstants[7]":"accentColorSolid = <SolidColorBrush Color=\"{ThemeResource SystemAccentColor}\" Opacity=\"1\" />","styleConstants[8]":"thick = 1","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[0].target":"Taskbar.TaskbarFrame > Grid#RootGrid","controlStyles[0].styles[0]":"Background:=$blurBackground","controlStyles[0].styles[1]":"CornerRadius=$taskbarCornerRadius","controlStyles[0].styles[2]":"BorderThickness=0.5","controlStyles[0].styles[3]":"BorderBrush:=$borderGradient","controlStyles[0].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[0].styles[5]":"Margin=0,1,0,3","controlStyles[0].styles[6]":"Padding=-145,1,12,-2","controlStyles[1].target":"Taskbar.TaskbarFrame#TaskbarFrame","controlStyles[1].styles[0]":"Transform3D:=<CompositeTransform3D TranslateX=\"0\"/>","controlStyles[2].target":"Grid#SystemTrayFrameGrid","controlStyles[2].styles[0]":"Background:=$blurBackground","controlStyles[2].styles[1]":"CornerRadius=$mainCornerRadius","controlStyles[2].styles[2]":"Margin=8,1,80,3","controlStyles[2].styles[3]":"BorderThickness=0.5","controlStyles[2].styles[4]":"BorderBrush:=$borderGradient","controlStyles[2].styles[5]":"BackgroundSizing=InnerBorderEdge","controlStyles[2].styles[6]":"Padding=-20,0,-20,0","controlStyles[2].styles[7]":"MaxHeight=30","controlStyles[3].target":"Taskbar.AugmentedEntryPointButton > Taskbar.TaskListButtonPanel","controlStyles[3].styles[0]":"Background:=$blurBackground","controlStyles[4].target":"Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator","controlStyles[4].styles[0]":"Height=44","controlStyles[4].styles[1]":"Width=40","controlStyles[4].styles[2]":"RadiusX=5","controlStyles[4].styles[3]":"RadiusY=5","controlStyles[4].styles[4]":"StrokeThickness=1.3","controlStyles[4].styles[5]":"Fill:=Transparent","controlStyles[4].styles[6]":"Visibility=Visible","controlStyles[4].styles[7]":"Stroke@InactiveNormal:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"{ThemeResource SystemAccentColorLight2}\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","controlStyles[4].styles[8]":"Stroke@InactivePointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[4].styles[9]":"Stroke@InactivePressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[4].styles[10]":"Stroke@ActiveNormal:=$accentGradient","controlStyles[4].styles[11]":"Stroke@ActivePointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[4].styles[12]":"Stroke@ActivePressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[4].styles[13]":"Stroke@MultiWindowNormal:=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"{ThemeResource SystemAccentColorLight2}\"/><GradientStop Offset=\"1\" Color=\"{ThemeResource SystemAccentColorDark2}\"/></LinearGradientBrush>","controlStyles[4].styles[14]":"Stroke@MultiWindowPointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight2}\" />","controlStyles[4].styles[15]":"Stroke@MultiWindowPressed:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight3}\" />","controlStyles[4].styles[16]":"Stroke@MultiWindowActive:=$accentGradient","controlStyles[5].styles[0]":"FontSize=20","controlStyles[6].target":"SystemTray.ChevronIconView","controlStyles[6].styles[0]":"Opacity=0","controlStyles[7].target":"SystemTray.NotifyIconView#NotifyItemIcon","controlStyles[7].styles[0]":"Padding=0","controlStyles[8].target":"SystemTray.OmniButton","controlStyles[8].styles[0]":"Padding=0","controlStyles[9].target":"SystemTray.Stack#ShowDesktopStack","controlStyles[9].styles[0]":"Margin=0,4,10,4","controlStyles[10].target":"SystemTray.ImageIconContent > Grid#ContainerGrid > Image","controlStyles[10].styles[0]":"Width=20","controlStyles[10].styles[1]":"Height=20","controlStyles[11].target":"Grid#OverflowRootGrid > Border","controlStyles[11].styles[0]":"Background:=$blurBackground","controlStyles[11].styles[1]":"Shadow:=","controlStyles[11].styles[2]":"CornerRadius=$mainCornerRadius","controlStyles[11].styles[3]":"BorderThickness=$thick","controlStyles[11].styles[4]":"BorderBrush:=$borderGradient","controlStyles[11].styles[5]":"BackgroundSizing=InnerBorderEdge","controlStyles[11].styles[6]":"Margin=-3,-3,-3,0","controlStyles[12].target":"Windows.UI.Xaml.Shapes.Rectangle#HorizontalTrackRect","controlStyles[12].styles[0]":"Height=8","controlStyles[12].styles[1]":"Margin=0","controlStyles[12].styles[2]":"Fill:=$overlayColor","controlStyles[13].target":"Windows.UI.Xaml.Shapes.Rectangle#HorizontalDecreaseRect","controlStyles[13].styles[0]":"Height=8","controlStyles[14].target":"Windows.UI.Xaml.Controls.TextBlock#volumeLevelText","controlStyles[14].styles[0]":"FontFamily=Tektur","controlStyles[14].styles[1]":"Margin=0,-2,0,0","controlStyles[15].target":"Windows.UI.Xaml.Controls.Grid#VolumeConfirmator","controlStyles[15].styles[0]":"Padding=8,0,3,0","controlStyles[15].styles[1]":"CornerRadius=$taskbarCornerRadius","controlStyles[16].target":"Windows.UI.Xaml.Controls.Grid#ConfirmatorMainGrid","controlStyles[16].styles[0]":"Background:=$blurBackground","controlStyles[16].styles[1]":"CornerRadius=$mainCornerRadius","controlStyles[16].styles[2]":"BorderThickness=$thick","controlStyles[16].styles[3]":"BorderBrush:=$borderGradient","controlStyles[16].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[16].styles[5]":"Margin=0,0,0,10","controlStyles[16].styles[6]":"Shadow:=","controlStyles[17].target":"Windows.UI.Xaml.Controls.Grid#BrightnessConfirmator","controlStyles[17].styles[0]":"Padding=15,0,17,0","controlStyles[17].styles[1]":"CornerRadius=$taskbarCornerRadius","controlStyles[18].target":"Microsoft.UI.Xaml.Controls.AnimatedIcon#BrightnessIcon","controlStyles[18].styles[0]":"Margin=0,-1,12,0","controlStyles[19].target":"Microsoft.UI.Xaml.Controls.ProgressBar#ProgressIndicator","controlStyles[19].styles[0]":"Margin=0,0,0,1","controlStyles[20].target":"Windows.UI.Xaml.Shapes.Rectangle#ProgressBarTrack","controlStyles[20].styles[0]":"Fill:=$inverseBWColor","controlStyles[20].styles[1]":"RadiusX=1.5","controlStyles[20].styles[2]":"RadiusY=1.5","controlStyles[21].target":"Windows.UI.Xaml.Shapes.Rectangle#DeterminateProgressBarIndicator","controlStyles[21].styles[0]":"Fill:=$accentColorSolid","controlStyles[22].target":"MenuFlyoutPresenter > Border","controlStyles[22].styles[0]":"Background:=$blurBackground ","controlStyles[22].styles[1]":"Shadow:=","controlStyles[22].styles[2]":"CornerRadius=$mainCornerRadius","controlStyles[22].styles[3]":"BorderThickness=$thick","controlStyles[22].styles[4]":"BorderBrush:=$borderGradient","controlStyles[22].styles[5]":"BackgroundSizing=InnerBorderEdge","controlStyles[5].target":"SystemTray.TextIconContent > Grid#ContainerGrid > SystemTray.AdaptiveTextBlock#Base > TextBlock#InnerTextBlock"}
   ```

* **Windows 11 Start Menu Styler**

    ```json
    {"theme":"TranslucentStartMenu","controlStyles[0].target":"Border#AcrylicBorder","controlStyles[0].styles[0]":"Background:=$CommonBgBrush","controlStyles[0].styles[1]":"BorderThickness=$thick","controlStyles[0].styles[2]":"BorderBrush:=$borderGradient","controlStyles[0].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[0].styles[4]":"CornerRadius=30","controlStyles[1].target":"Border#AcrylicOverlay","controlStyles[1].styles[0]":"Visibility=Collapsed","controlStyles[2].target":"Border#BorderElement","controlStyles[2].styles[0]":"Background:=$CommonBgBrush","controlStyles[2].styles[1]":"BorderThickness=$thick","controlStyles[2].styles[2]":"BorderBrush:=$borderGradient","controlStyles[2].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[2].styles[4]":"CornerRadius=10","controlStyles[3].target":"Border#AppBorder","controlStyles[3].styles[0]":"Background:=$CommonBgBrush","controlStyles[3].styles[1]":"BorderThickness=$thick","controlStyles[3].styles[2]":"BorderBrush:=$borderGradient","controlStyles[3].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[3].styles[4]":"CornerRadius=30","controlStyles[4].target":"Border#AccentAppBorder","controlStyles[4].styles[0]":"Background:=$CommonBgBrush","controlStyles[4].styles[1]":"BorderThickness=$thick","controlStyles[4].styles[2]":"BorderBrush:=$borderGradient","controlStyles[4].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[4].styles[4]":"CornerRadius=30","controlStyles[5].target":"StartDocked.StartSizingFrame","controlStyles[5].styles[0]":"MaxHeight=520","controlStyles[6].target":"Windows.UI.Xaml.Controls.Grid#ShowMoreSuggestions","controlStyles[6].styles[0]":"RenderTransform:=<TranslateTransform Y=\"-408\" />","controlStyles[7].target":"Windows.UI.Xaml.Controls.Grid#NoTopLevelSuggestionsText","controlStyles[7].styles[0]":"Height=0","controlStyles[8].target":"StartMenu.PinnedList","controlStyles[8].styles[0]":"Height=340","controlStyles[8].styles[1]":"Background:=$CommonBgBrush","controlStyles[9].target":"Windows.UI.Xaml.Controls.Grid#ShowMoreSuggestions > Windows.UI.Xaml.Controls.Button > Windows.UI.Xaml.Controls.ContentPresenter > Windows.UI.Xaml.Controls.StackPanel > Windows.UI.Xaml.Controls.TextBlock","controlStyles[9].styles[0]":"Text=Recommended","controlStyles[10].target":"Windows.UI.Xaml.Controls.Border#DropShadow","controlStyles[10].styles[0]":"CornerRadius=30","controlStyles[11].target":"Windows.UI.Xaml.Controls.Border#StartDropShadow","controlStyles[11].styles[0]":"CornerRadius=30","controlStyles[12].target":"StartDocked.LauncherFrame > Grid#RootGrid > Grid#RootContent > Grid#MainContent > Grid#InnerContent > Rectangle","controlStyles[12].styles[0]":"Visibility=Collapsed","controlStyles[13].target":"StartDocked.SearchBoxToggleButton","controlStyles[13].styles[0]":"Visibility=Collapsed","controlStyles[14].target":"Windows.UI.Xaml.Controls.Grid#AllAppsRoot","controlStyles[14].styles[0]":"Margin=0,0,0,40","controlStyles[15].target":"Windows.UI.Xaml.Controls.Grid#UndockedRoot","controlStyles[15].styles[0]":"Margin=0,0,0,40","controlStyles[16].target":"StartDocked.NavigationPaneView#NavigationPane > Windows.UI.Xaml.Controls.Grid#RootPanel","controlStyles[16].styles[0]":"Margin=0,-10,0,10","controlStyles[17].target":"StartDocked.AppListViewItem > Grid@CommonStates > Border","controlStyles[17].styles[0]":"CornerRadius=50","controlStyles[18].target":"StartDocked.NavigationPaneButton#UserTileButton > Grid > Border#BackgroundBorder","controlStyles[18].styles[0]":"CornerRadius=18","controlStyles[19].target":"StartDocked.NavigationPaneButton#PowerButton > Windows.UI.Xaml.Controls.Grid@CommonStates > Windows.UI.Xaml.Controls.Border#BackgroundBorder","controlStyles[19].styles[0]":"Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\"1\" Opacity=\"1\"/>","controlStyles[19].styles[1]":"BorderBrush@Normal:=<AcrylicBrush TintColor=\"{ThemeResource SurfaceStrokeColorDefault}\" FallbackColor=\"{ThemeResource SurfaceStrokeColorDefault}\" TintOpacity=\"0\" TintLuminosityOpacity=\".1\" Opacity=\"1\"/>","controlStyles[19].styles[2]":"CornerRadius=30","controlStyles[19].styles[3]":"BorderThickness=5","controlStyles[19].styles[4]":"Margin=-7","controlStyles[19].styles[5]":"BorderBrush@PointerOver:=<AcrylicBrush TintColor=\"{ThemeResource SystemAccentColor}\" FallbackColor=\"{ThemeResource SystemAccentColor}\" TintOpacity=\".8\" TintLuminosityOpacity=\".5\" Opacity=\"1\"/>","controlStyles[20].target":"StartDocked.AppListView#NavigationPanePlacesListView > Windows.UI.Xaml.Controls.Border","controlStyles[20].styles[0]":"Margin=0,0,15,0","webContentStyles[0].target":"","webContentStyles[0].styles[0]":"","webContentCustomJs":"","disableNewStartMenuLayout":"0","styleConstants[0]":"CommonBgBrush=<WindhawkBlur BlurAmount=\"3\" TintColor=\"#88000000\"/>","styleConstants[1]":"borderGradient=<LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","styleConstants[2]":"thick=1"}
    ```

* **Windows 11 Notification Center Styler**

    ```json
    {"theme":"Matter","styleConstants[0]":"blurBackground = <WindhawkBlur BlurAmount=\"3\" TintColor=\"#88000000\" />","styleConstants[1]":"blurOverlay = <WindhawkBlur BlurAmount=\"3\" TintColor=\"#66000000\" />","styleConstants[2]":"borderGradient = <LinearGradientBrush StartPoint=\"0.5,0\" EndPoint=\"0.5,1\"><GradientStop Offset=\"0\" Color=\"#cccccc\"/><GradientStop Offset=\"1\" Color=\"#262626\"/></LinearGradientBrush>","styleConstants[3]":"themeShadow = <ThemeShadow/>","styleConstants[4]":"thick = 1","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","controlStyles[0].target":"Border#JumpListRestyledAcrylic","controlStyles[0].styles[0]":"Background:=$blurBackground","controlStyles[0].styles[1]":"BorderThickness=$thick","controlStyles[0].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[0].styles[3]":"BorderBrush:=$borderGradient","controlStyles[0].styles[4]":"Shadow:=$themeShadow","controlStyles[1].target":"Grid#NotificationCenterGrid","controlStyles[1].styles[0]":"Background:=$blurBackground","controlStyles[1].styles[1]":"BorderThickness=$thick","controlStyles[1].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[1].styles[3]":"BorderBrush:=$borderGradient","controlStyles[1].styles[4]":"Shadow:=$themeShadow","controlStyles[2].target":"Grid#CalendarCenterGrid","controlStyles[2].styles[0]":"Background:=$blurBackground","controlStyles[2].styles[1]":"BorderThickness=$thick","controlStyles[2].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[2].styles[3]":"BorderBrush:=$borderGradient","controlStyles[2].styles[4]":"Shadow:=$themeShadow","controlStyles[3].target":"ScrollViewer#CalendarControlScrollViewer","controlStyles[3].styles[0]":"Background:=$blurOverlay","controlStyles[4].target":"Border#CalendarHeaderMinimizedOverlay","controlStyles[4].styles[0]":"Background:=$blurOverlay","controlStyles[5].target":"ActionCenter.FocusSessionControl#FocusSessionControl > Grid#FocusGrid","controlStyles[5].styles[0]":"Background:=$blurOverlay","controlStyles[6].target":"MenuFlyoutPresenter > Border","controlStyles[6].styles[0]":"Background:=$blurBackground","controlStyles[6].styles[1]":"BorderThickness=$thick","controlStyles[6].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[6].styles[3]":"BorderBrush:=$borderGradient","controlStyles[6].styles[4]":"Shadow:=$themeShadow","controlStyles[7].target":"Grid#ControlCenterRegion","controlStyles[7].styles[0]":"Background:=$blurBackground","controlStyles[7].styles[1]":"BorderThickness=$thick","controlStyles[7].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[7].styles[3]":"BorderBrush:=$borderGradient","controlStyles[7].styles[4]":"Shadow:=$themeShadow","controlStyles[8].target":"ContentPresenter#PageContent > Grid > Border","controlStyles[8].styles[0]":"Background:=$blurOverlay","controlStyles[9].target":"QuickActions.ControlCenter.AccessibleWindow#PageWindow > ContentPresenter > Grid#FullScreenPageRoot > ContentPresenter#PageHeader","controlStyles[9].styles[0]":"Background:=$blurOverlay","controlStyles[10].target":"ScrollViewer#ListContent","controlStyles[10].styles[0]":"Background:=$blurOverlay","controlStyles[11].target":"Border#ToastBackgroundBorder2","controlStyles[11].styles[0]":"Background:=$blurBackground","controlStyles[11].styles[1]":"BorderThickness=$thick","controlStyles[11].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[11].styles[3]":"BorderBrush:=$borderGradient","controlStyles[12].target":"JumpViewUI.SystemItemListViewItem > Grid#LayoutRoot > Border#BackgroundBorder","controlStyles[12].styles[0]":"Background@Normal:=Transparent","controlStyles[13].target":"Grid#NotificationCenterTopBanner","controlStyles[13].styles[0]":"Background:=$blurOverlay","controlStyles[14].target":"Windows.UI.Xaml.Controls.Grid#MediaTransportControlsRegion","controlStyles[14].styles[0]":"Background:=$blurBackground","controlStyles[14].styles[1]":"BorderThickness=$thick","controlStyles[14].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[14].styles[3]":"BorderBrush:=$borderGradient","controlStyles[15].target":"Windows.UI.Xaml.Controls.Primitives.RepeatButton#PreviousButton > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter@CommonStates","controlStyles[15].styles[0]":"Background@Normal:=$blurOverlay","controlStyles[16].target":"Windows.UI.Xaml.Controls.Button#PlayPauseButton > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter@CommonStates","controlStyles[16].styles[0]":"Background@Normal:=$blurOverlay","controlStyles[17].target":"Windows.UI.Xaml.Controls.Primitives.RepeatButton#NextButton > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter@CommonStates","controlStyles[17].styles[0]":"Background@Normal:=$blurOverlay","controlStyles[18].target":"Windows.UI.Xaml.Controls.Grid > Windows.UI.Xaml.Controls.Border#ItemOpaquePlating","controlStyles[18].styles[0]":"Background:=$blurOverlay","controlStyles[12].styles[1]":"Background@PointerOver:=$blurOverlay","controlStyles[12].styles[2]":"Background@Pressed:=$blurBackground","controlStyles[19].target":"JumpViewUI.SystemItemListViewItem > Grid#LayoutRoot > Border#BackgroundBorder > Grid > TextBlock","controlStyles[19].styles[0]":"Foreground@Normal:={ThemeResource SystemBaseHighColor}","controlStyles[19].styles[1]":"Foreground@PointerOver:={ThemeResource SystemAccentColorLight1}","controlStyles[20].target":"JumpViewUI.SystemItemListViewItem > Grid#LayoutRoot > Border#BackgroundBorder > Grid > ContentPresenter","controlStyles[20].styles[0]":"Opacity@Normal:=0.8","controlStyles[20].styles[1]":"Opacity@PointerOver:=1.0"}
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
