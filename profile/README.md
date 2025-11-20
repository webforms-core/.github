# WebForms Core Technology

WebForms Core is an advanced technology for manipulating HTML tags on the server. It is a radical technology that eliminates the need for front-end development. WebForms Core is the easiest way to build web-based systems, because you only need to design an HTML page and manage it using server-side code.

**The Renaissance of the Server**

> WebForms Core uses a **server-command/client-execution** approach rather than the conventional **request–response cycle** model that other web frameworks use to handle state and render the UI.

In this technology, the [WebForms class](https://github.com/webforms-core/Web_forms_classes) on the server automatically communicates with the [WebFormsJS](https://github.com/webforms-core/Web_forms) library on the client side. To use this technology, you only need to include the WebFormsJS library in the head section of the HTML page and use the WebForms class on the server side.

## Example

```csharp
WebForms form = new WebForms();

form.AddTag("<form>", "h3");
form.AddText("<h3>-1", "File was upload.");
form.AddTag("<form>", "img");
form.SetAttribute("<form>|<img>-1", "src", FilePath);
form.SetWidth("<form>|<img>-1", 400);

Write(form.Response());
```

Result
-
![WebForms Core Technology - Image Upload Example](https://github.com/user-attachments/assets/57dc4b66-e051-4157-b162-515a1438aac7)
-
