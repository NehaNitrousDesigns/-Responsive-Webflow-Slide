# -Responsive-Webflow-Slide

After adding this script to your Webflow project, the following changes will occur:

Responsive Slide Container Height:
The height of the container with the class .outsource-form-slider will automatically adjust to match the height of the currently visible slide. This ensures that the slider container always fits the content of the active slide, preventing overflow or empty space issues.

Smooth Transitions:
As you navigate through the slides, the container will smoothly resize to accommodate the content of each slide, creating a more polished and dynamic user experience.

Dynamic Height Adjustment:
If the content within a slide changes (e.g., due to dynamic content loading or user interactions that alter the slide’s content height), the container’s height will adjust accordingly, maintaining a consistent layout.

Implementation Steps:
Add Classes to Elements:

Ensure that your slides have the class form-slide.
Ensure that the container of the slides has the class outsource-form-slider.
Insert the Script:
Place the following script in an HTML embed element or in the custom code section of your Webflow project (usually in the <body> or <head> section, depending on when you want it to run):
