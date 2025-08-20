<div align="center">
   <img src="https://github.com/user-attachments/assets/52859f5b-900a-46da-b026-529259fcde62" alt="Flutter-X-Dart Logo" width="60%" height="250%">
</div>

# Flutter & DART

This `Repository` serves as a **comprehensive record** of my `learnings`, `experiments`, and `progress` as I deepen my understanding of `DART` Programming and develop applications with `Flutter`.<br>

<div align="center">
   
   **📌 Discover more of my work in my [`Other Repositories`](https://github.com/Yashvant-Chhapwale-Course-Work/Yashvant-Chhapwale-Course-Work)!**
</div>

---

## About Flutter

`Flutter` is an **Open-source** `UI SDK (Software_Development_Toolkit)` created by **`Google`**.<br>

- `Utility:` A **Utility** is a **Single-Purpose CSS_Class** that applies **Styling** for one specific **Style_Attribute**.
- `Utility-First:` **Tailwind** encourages you to use **Utility_Classes** which are your **First and Main Styling_Method** before using External_CSS or Plugins.
- `CSS_Framework`: **Tailwind** is a **CSS_Framework** that provides a **predefined set of Styles, Utility_Classes, and Conventions** that help you build UIs quickly.

### Features:

- `Utility-First Approach:` The **Utility_Classes** are your First and Main Styling_Method.
- `Responsive Design:` Easily build **UI_layouts that Adapt to different Screen_Sizes** with Mobile-First breakpoints.
- `Customizable:` **Fully Customizable via the `tailwind.config.js` file** for colors, spacing, fonts, and more.
- `Component-Friendly:` Encourages **Reusable UI_Components** without the need to leave HTML.
- `JIT(Just-In-Time) Engine:` **Utilizes Just-In-Time Compilation** for fast build times and smaller final CSS output. It generates the CSS you need, only when you need it, instead of generating everything up front.
  <br>

<div align="center">
   
   **📌 Visit the [Official_Documentation](https://tailwindcss.com/docs) to know more about `Tailwind_CSS`.**
</div>

---

<div align="center">
 <h1>Index</h1>
</div>

<div align="center">
 
| TITLE                                                                                                                                           | SECTION_LINK                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| 1.  **Tailwind Version Selection**                                                                                                              |  [` 🔗CONTENT `](#tailwind-version-selection)                                                |
| 2.  **Tailwind Installation and Setup**                                                                                                         |  [` 🔗CONTENT `](#tailwind-installation-and-setup)                                           |
| 3.  **Tailwind_Version Verification**                                                                                                           |  [` 🔗CONTENT `](#tailwind_version-verification)                                             |
| 4.  **Tailwind_CSS VS_Code Extension**                                                                                                          |  [` 🔗CONTENT `](#tailwind_css-vs_code-extension)                                            |
| [**BEGINNER**](#beginner---level)                                                                                                                                                                                                               |
| 5.  **Basic `Layout` Utility_Classes**                                                                                                          |  [` 🔗CONTENT `](#basic-layout-utility_classes)                                              |
| 6.  **`Typography` Utility_Classes**                                                                                                            |  [` 🔗CONTENT `](#typography-utility_classes)                                                |
| 7.  **Element `Shadows` Utility_Classes**                                                                                                       |  [` 🔗CONTENT `](#element-shadows-utility_classes)                                           |
| 8.  **Tailwind `Backgrounds` and `Colors`**                                                                                                     |  [` 🔗CONTENT `](#tailwind-backgrounds-and-colors)                                           |
| [**INTERMEDIATE**](#intermediate---level)                                                                                                                                                                                                       |
| 9.  **Advanced `Layout` Utility_Classes: [`flex`](#flexbox-layout), [`grid`](#grid-layout)**                                                    |  [` 🔗CONTENT `](#advanced-layout-utility_classes)                                           |
| 10. **`Responsive` Layout_Build**                                                                                                               |  [` 🔗CONTENT `](#responsive-layout_build)                                                   |
| 11. **Tailwind's `Dark Mode` Support**                                                                                                          |  [` 🔗CONTENT `](#tailwinds-dark-mode-support)                                               |
| 12. **Tailwind's `Variant Prefixes`**                                                                                                           |  [` 🔗CONTENT `](#tailwinds-variants)                                                        |
| [**ADVANCED**](#advanced---level)                                                                                                                                                                                                               |
| 13. **`Transformations`**                                                                                                                       |  [` 🔗CONTENT `](#transform-utilities)                                                       |
| 14. **`Transitions` & `Animations`**                                                                                                            |  [` 🔗CONTENT `](#transition-and-animation-utilities)                                        |
| 15. **Customizing Tailwind_Utilities with `tailwind.config.js`** [`Update v4: (CSS-First Configuration)`](#tailwind_v4-css-first-configuration) |  [` 🔗CONTENT `](#customizing-tailwind-with-tailwindconfigjs)                                |

</div>

---

## Tailwind Version Selection
- Visit the **Tailwind_CSS** [**`Docs`**](#https://tailwindcss.com/docs) Page.
- Select the **Required** `Tailwind_Version` from the **Version_Dropdown**.
  ![`Version_Dropdown`](https://github.com/user-attachments/assets/32b916da-dbf5-432b-b734-4b8002eef299)<br>
- The `Docs` will provide appropriate Information and Installation Guide with respect to the selected `Tailwind_Version`.
<br>

---
<br>

## Tailwind Installation and Setup

### 1.Using Play_CDN(Content Delivery Network) [QUICKEST METHOD]:
- The `Play CDN` lets you load `Tailwind's Core_Utilities` into your project **without any Build Step**.
- `Without any Build Step:` Normally, with a Full Tailwind_Setup, you’d need `Node_Js`, `npm` (To install Tailwind) and sometimes a Build_Tool like `Vite`. But, with `Play_CDN`, you can skip all of that — **No Configuration**, **No Installation**, **No Compiling**.
- All the **Utility_Classes** are **preloaded** via the CDN Servers!
- It is great for **Prototyping** and **Demos** but `Not Applicable in a Production Environment` as it is **Heavy** (Loads all utilities at once, even if you require a few), **No Customization** (You can’t configure Tailwind themes, colors, etc. via `tailwind.config.js` File), **No JIT** (No Just-In-Time Compiler Used), **No Purging Of Unused Classes**, etc.
- Go to [`Play_CDN Docs`](https://tailwindcss.com/docs/installation/play-cdn).
- **Copy** the `CDN Script` from the Page:
  ```
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  ```
  ![Play_CDN Script](https://github.com/user-attachments/assets/900289e2-7731-437a-b633-f71047743411)<br>
- Paste it inside the `<head> Tag` of your `HTML`:
  ```
  <head>
     <meta charset="UTF-8" />
     <meta name="viewport" content="width=device-width, initial-scale=1.0" />
     <title>Tailwind-Bootcamp</title>

     <!-- Play_CDN Script -->
     <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  </head>
  ```

- Now you are ready to use `Tailwind's Utility_Classes` directly in your `HTML` without any Setup or Build Process!
  <br>
  <br>
  <br>

### 2.Using Tailwind_CLI:
- Tailwind CLI is the official Command-Line Interface provided by Tailwind CSS that allows you to:
  - **Compile** your Tailwind CSS from Source to a **usable CSS_File** (typically `output.css`).
  - **Without needing a Build_Tool** (Ex: Vite).
- `Note:` You need to [`Install and Setup Node_Js`](https://nodejs.org/en/download) for this Method.
- Go to [`Tailwind_CLI Docs`](https://tailwindcss.com/docs/installation/tailwind-cli).
- **Copy** and **Run** the `npm Command` from the Page, in your `Terminal`, to install `Tailwind_CSS` and `Tailwind_CLI`:
  ```
  npm install tailwindcss@latest @tailwindcss/cli@latest
  ```
- Next, **Import** `Tailwind_CSS` in you **Main CSS_File** (`style.css`).<br>
  `For Ex:` Suppose **style.css**:
  ```
  @import "tailwindcss";
  ```
- **Run** the `Tailwind_CLI Tool`, to scan your **Project_Files** for **Utility_Classes** and **Build your CSS**, using the following `npx Command`:
  ```
  npx @tailwindcss/cli -i ./path/to/main.css -o ./path/to/output.css --watch
  ```
  - `-i:` It specifies the path to your **Input CSS_File** (`./path/to/main.css` or `./path/to/style.css`).
  - `-o:` It specifies the path where you want to define your **Output CSS_File** (`./path/to/output.css`).
  - `--watch:` Keeps **Watching / Scanning** the Project_Files(`.html`) for changes while you develop.
  - `NOTE:` You need to **Run** the **Above Command** `Each Time you Start your Project` to **Compile** and **Watch** `Tailwind CSS` for changes.
- Add the **newly compiled** `CSS_File` (`output.css`) inside the `<head> Tag` of your `HTML`:

  ```
  <head>
     <meta charset="UTF-8" />
     <meta name="viewport" content="width=device-width, initial-scale=1.0" />
     <title>Tailwind-Bootcamp</title>

     <!-- Linking output.css -->
     <link href="./output.css" rel="stylesheet">
  </head>
  ```

  ![Tailwind_CLI](https://github.com/user-attachments/assets/1d4d70f4-f4f5-48c5-90a3-4c59a6da7e11)<br>

- Now you are all set to use `Tailwind's Utility_Classes` in your Project efficiently!
  <br>
  <br>
  <br>

### 3.Using Vite:
- `Vite` is a **Modern Build_Tool** and **Development_Server** that dramatically improves the `UI_development (Frontend)` experience.
- **Prerequisites:**
  - You need to [`Install and Setup Node_Js`](https://nodejs.org/en/download) for this Method.
  - You also need to [`Utilize the Vite Build_Tool`](https://vite.dev/guide/), by using the following **Command**:
    ```
    npm create vite@latest my-app --template react
    ```
    After **Executing** the **Command**, Follow the `Guided_Steps` shown in the `Terminal` to Setup `React` using the `Vite Build Tool`.
- Go to [`Tailwind_CLI Docs`](https://tailwindcss.com/docs/installation/tailwind-cli).
- **Copy** and **Run** the `npm Command` from the Page, in your `Terminal`, to install `Tailwind` and `@tailwindcss/vite`:
  ```
  npm install tailwindcss@latest @tailwindcss/vite@latest
  ```
- Next, Add the `@tailwindcss/vite` **Plugin** to your `Vite_Configuration` (i.e, `vite.config.js` or `vite.config.ts` File):<br>
  `For Ex:` Suppose **vite.config.js**:

  ```
  import path from "path";
   import { defineConfig } from "vite";
   import react from "@vitejs/plugin-react";

   // Import @tailwindcss/vite Plugin
   import tailwindcss from "@tailwindcss/vite";

   // https://vite.dev/config/
   export default defineConfig({
     plugins: [react(), tailwindcss()], //Add TailwindCSS to the List_of_Plugins
     resolve: {
       alias: {
         "@": path.resolve("./src"),
       },
     },
   });
  ```

- Next, **Import** `Tailwind_CSS` in you **Main CSS_File** (`index.css`).<br>
  `For Ex:` Suppose **index.css**:
  ```
  @import "tailwindcss";
  ```
- Make sure the `Compiled CSS_File` (`App.css`) is imported inside your `App.jsx` or `App.tsx` File:<br>
  `For Ex:` Suppose **App.jsx**:

  ```
  import "./App.css";
   import { Button } from "./components/ui/button";

   function App() {
     return (
       <>
         <Button>hello</Button>
       </>
     );
   }

   export default App;
  ```

  ![Tailwind_for_Vite](https://github.com/user-attachments/assets/946af695-d2c9-4856-94b9-2c27bbc1bb2e)<br>

- Now you are all set to use `Tailwind's Utility_Classes` in your **Vite: React_Project** efficiently!
  <br>

<div align="center">
   
   **`Note:` The `Setup_Steps` in the Above Methods are aligned with the Latest `Tailwind_CSS Version` at the Time, i.e., `Tailwind_CSS v4.1`.**
</div>
<br>

---
<br>

## Tailwind_Version Verification
- Open your `Terminal` or `Command_Prompt`.
- Paste the following **CCommand** in your `Terminal` to verify which `Tailwind_Version` you're using:
  ```
  npx tailwindcss -v
  ```
  ![`npx tailwindcss -v`](https://github.com/user-attachments/assets/ddf45185-ef2a-422b-98b4-df8e7eef43f5)<br>
<br>
   
---
<br>

## Tailwind_CSS VS_Code Extension
- You can **Install** the following `Extension` in VS_Code for proper **formatting and ease** in `Tailwind_Code`. 
![Tailwind_CSS IntelliSense](https://github.com/user-attachments/assets/1b9ca91a-0b94-490c-aaa1-016b945dcfba)<br>
<br>

---

