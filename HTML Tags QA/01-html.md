#### 1. What is the purpose of the `<!DOCTYPE>` declaration in HTML?

##### Answer:
- In this `<!DOCTYPE>`, it is not case sensitive. you can use lowercase as well.
- It follows HTML5 documents.
- Ensures consistent rendering.


| Feature                 | **HTML4**                                                                    | **HTML5**                                                                                     |
| ----------------------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Doctype Declaration** | Long and complex:<br>`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"...>` | Simple:<br>`<!DOCTYPE html>`                                                                  |
| **Structure Tags**      | No semantic structure tags                                                   | Introduces semantic tags like `<header>`, `<footer>`, `<article>`, `<section>`, `<nav>`, etc. |
| **Multimedia Support**  | Requires plugins (Flash, etc.) for audio/video                               | Native support for `<audio>` and `<video>`                                                    |
| **Form Enhancements**   | Limited input types                                                          | New input types: `email`, `date`, `number`, `range`, etc.                                     |
| **Graphics Support**    | No support for drawing                                                       | Supports `<canvas>` and SVG for drawing graphics                                              |
| **Storage**             | Relies on cookies                                                            | Supports Web Storage: `localStorage`, `sessionStorage`                                        |
| **APIs & Features**     | Lacks built-in APIs                                                          | Supports APIs like Geolocation, Web Workers, Offline Web Apps                                 |
| **Mobile Support**      | Not designed for mobile                                                      | Designed with mobile-first approach in mind                                                   |
| **Error Handling**      | Browsers handled inconsistently                                              | Standardized parsing rules across browsers                                                    |
