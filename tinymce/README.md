# TinyMCE Open Source

TinyMCE Open Source is a self-hosted, customizable rich text editor that provides a powerful WYSIWYG editing experience for web applications. This repository offers an open-source version of TinyMCE for developers who want full control over their editor setup.

## 🚀 Features

- 🎨 **Customizable UI & Plugins** – Modify the editor to fit your needs.
- 🔒 **Self-Hosted** – No external dependencies or CDNs required.
- ⚡ **Lightweight & Fast** – Optimized for performance.
- 📜 **Open Source** – Fully free to use and modify.
- 🌎 **Multi-Language Support** – Easily add translations.

## 📢 Use All Premium Features for Free

You can access all premium features of TinyMCE using the following URL:

```sh
https://md-mh.github.io/html_css_js/tinymce/tinymce.min.js
```

This repository serves as the source project for the above URL.

## 🛠️ Usage

### 1️⃣ Include TinyMCE in Your Project

```html
<script src="https://md-mh.github.io/html_css_js/tinymce/tinymce.min.js"></script>
```

### 2️⃣ Initialize TinyMCE

```html
<script>
  tinymce.init({
    selector: "textarea",
    plugins: "lists link image code",
    toolbar:
      "undo redo | bold italic | alignleft aligncenter alignright | code",
  });
</script>
```
