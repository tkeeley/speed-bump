Confirmation Popup with URL Parameter
This HTML, CSS, and JavaScript code provides a confirmation popup with a "speed bump" URL parameter for external links while allowing internal links to function normally.

How It Works
When a user clicks on an external link (a link leading to a different domain), a confirmation popup appears.

The popup asks the user if they are sure they want to leave the website and continue to the external link.

The user can choose to click "Yes" or "No."

If the user clicks "Yes," the code appends a ?speed-bump=true query parameter to the external link and then redirects the user to that link.

If the user clicks "No," the popup closes, and they remain on the current page.

Internal links (links leading to the same domain) work without triggering the confirmation popup and maintain their regular functionality.
