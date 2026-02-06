## About the Visitor Counter

This website aims to faithfully recreate the style and structure of early 2000s personal websites.  
As part of this restoration, it also includes an external visitor counter service that was commonly used at that time: **RAYS COUNTER**.

### Why does the counter not work on GitHub Pages?

This site is deployed on **GitHub Pages**, which is served over **HTTPS**.  
However, the original **RAYS COUNTER** service was designed in an era when most websites were served over **HTTP**, and it does not fully support modern HTTPS environments.

When an HTTPS page tries to load external resources that are not fully compatible with HTTPS, modern browsers will block or interrupt the connection for security reasons (e.g. mixed content or connection reset).

As a result:

- The counter may work correctly in local environments (such as `file://` or `http://localhost`)
- The counter does **not** display properly when deployed on GitHub Pages (HTTPS)

This behavior is not caused by an error in the site’s code or GitHub Pages configuration, but by the **limited HTTPS compatibility of the original counter service**.

### Why is the counter still included?

The purpose of this project is not to provide a fully modern or functional website, but to **recreate the visual and cultural experience of early personal websites as accurately as possible**.

Visitor counters were an iconic element of that era, so the counter is intentionally preserved as a **stylistic and nostalgic feature**, even though it may not function in modern HTTPS environments.

### Notes

- This is a personal, non-commercial project
- No real user data is collected
- The counter is not used as an actual traffic measurement tool

Thank you for your understanding and for visiting.

© ヤチヨのお部屋 / since 2003
