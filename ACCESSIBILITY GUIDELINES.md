# Accessibility Guidelines

Accessibility guidelines, such as the Web Content Accessibility Guidelines (WCAG), provide standards for making web content more accessible to people with disabilities. These guidelines are organized under four principles: perceivable, operable, understandable, and robust. They include testable success criteria at three levels (A, AA, AAA) to ensure content is accessible to a wide range of users, including those with visual, auditory, physical, and cognitive disabilities. By following these guidelines, developers can create inclusive digital experiences that remove barriers and enable equal access for all .

## Background

In terms of ADA accessibility guidelines a background color is considered decorative when it's purely for visual enhancement and doesn't contribute any essential information. If the background color is used to display information, such as text, or to highlight important elements, it's not considered decorative and must meet certain contrast requirements

## Code

* Use unique title for each page or view
* Make sure that viewport zoom is not disabled * Use landmark for important content
* Use only oneH1 per page
* H1 should not be a hidden style that references the page name
* Form buttons have a descriptive value
* Ensure each web page has the correct language assigned
* Images that do not convey   content, are decorative, or contain content that is all ready conveyed in text are given empty alternative text (alt="") or implemented as CSS backgrounds. All linked images have descriptive alternative text If an image is purely for visual appeal and doesn't add any meaning or information to the page, it should be treated as decorative
* If the content of an image is already conveyed in the surroundingtext,    the image is redundant and should not be assigned anyalternative    text, or it can be implemented as a CSS backgroundimage.

  * Using CSS background images for decorative purposes allows the image to be
    removed from the page's semantic structure, which can also reduce accessibility issues.
  * All images that are part of a link and are essential to the link's functionality need descriptive alternative text, so that screen reader users can understand the purpose of the link.

  Example:

  * If an image is a button that reads "submit", the alt text would be
    "submit" or something else that  provides context to the
    functionality of the button, and is not just "button" or "image"

  * For images that do not require alternative text, use an empty alt
    attribute: `<img src="image.jpg" alt="">`  Ensure each web page has
    the correct language assigned

## Contrast

* Ensure a high contrast between text sections and their backgrounds with a ratio of at least 4.5:1`<img width="350" alt="Image of buttons with good and bad contrast ratio" src="https://www.emailonacid.com/wp-content/uploads/2021/08/image3.png">`
* You cannot round a contrast ratio up to 4.5:1
* Ensure that information conveyed by color is visually evident without color
* Large text  at least 18 point (typically 24px) or 14 point (typically 18.66px) and bold - has a contrast ratio of at least 3:1.

## Disabled Buttons

* No Contrast Requirement:
* WCAG 2.1 doesn't explicitly require disabled elements to meet the same color contrast ratios as active elements.

* Focus on Visibility:
  * The primary focus should be on ensuring disabled buttons are still visible and distinguishable from active elements, not necessarily meeting the same contrast as active elements.
* Alternative Approaches:
  * Consider using other visual cues, like subtle graying or a different color, to indicate a disabled state.
* Avoid Disappearing Buttons:
  * If a button is disabled, it should remain visible to the user, rather than disappearing, as this can be confusing.

Accessibility Best Practices:

* Clear Labeling:
  * Use clear and concise labels for buttons, even when disabled, to help users understand their purpose.
* Keyboard Navigation:
  * Ensure disabled buttons are navigable with the keyboard and that users can't accidentally focus on them.
* Assistive Technology:
  * Make sure disabled buttons are detectable by assistive technologies like screen readers, using attributes like `aria-disabled="true"`
* User Experience:
  * Consider the user experience and avoid disabling buttons unnecessarily. If possible, provide feedback to the user instead of disabling the button.
* Hover States:
  * Ensure that hover states are still distinguishable even when the button is disabled.

Examples of Accessible Disabled Buttons:

* Visual Cue:
  * A subtle graying or a different color to indicate a disabled state.
* Tooltip:
  * A tooltip that explains why the button is disabled.
* Clear Labeling:
  * A clear label that indicates the button's purpose and why it's currently unavailable.
* ARIA Attributes:
  * Using `aria-disabled="true"` to inform screen readers that the button is disabled.

## Documents

* All linked documents not in HTML format, such as PDFs, presentations, spreadsheets, and Word documents, meet their type’s basic accessibility requirements
  * Contrast
  * Tabbing through sections
* PDFs need to be tagged in the valid reading order for accessibility.

## Errors

* Ensure error messages are specific and provide guidance

## Form Field Labels

* Place form field labels next to the text fields. This allows users who use assistive technologies to interact with the form
* Optimize color contrast and text readability for the visually impaired

## Labels

* Use headings correctly to organize the structure of content
  * Heading 1 (H1): This should be the main title or the overall topic of the page or document.
  * Heading 2 (H2): Use for major sections or subtopics within the main topic.
  * Heading 3 (H3): Use for subsections of H2 sections.
  * Heading 4 (H4) and onwards: Continue using H4, H5, and H6 to further refine subtopics, following a logical hierarchy.
  * Avoid Skipping Levels: Do not skip heading levels (e.g., go from H1 to H3 without an H2).
  * Don't use headings for visual formatting: Headings should be used to structure content, not just for making text look bigger or bolder.
  * Use CSS for styling: If you want to change the appearance of headings, use CSS to style them, rather than using an inappropriate heading level for visual purposes.
  * Descriptive and Concise Headings: Make sure your headings are clear and accurately reflect the content they introduce.
  * Assistive Technology: Well-structured headings are crucial for users of assistive  technology like screen readers, as they help navigate and understand the content.
  * Think of a table of contents or essay outline: When organizing your headings, consider how you would structure a table of contents or an essay outline.
* Unique page titles
* Use Aria role tags for each element
* Ensure that web elements don’t change when they get input

## Links

* If the links change color on hover or focus each of the colors in these states must also have at least a 4.5:1 contrast ratio difference with the background
* Color alone is not used to distinguish links from surrounding text unless the contrast ratio between the link and the surrounding text is at least 3:1 and an additional distinction (e.g., it becomes underlined) is provided when the link is hovered over and receives keyboard focus.
* Links should have a text description that can be read by a screen reader
* Links should be underlined by default in a body of text

## Menus and Buttons

* Ensure that menus and buttons appear in the same order and presentation throughout the site
* Ensure menus, icons, and buttons appear consistently
  When a button has an icon make sure that you use a descriptive label

## Multimedia

* Provide transcript for video and audio
* Provide closed captions for videos with audio
* Provide controls when auto-playing is enabled
* Ensure that there are no seizures inducing content
* Flashing more than 3 times in one second
* Provide users with audio description for video content
* Include alt text for images
* Provide closed captions for live videos

## Navigation

* Ability to use keyboard to navigate
* Ensure that users can navigate your website using keyboard shortcuts
  * See appendix
* Provide a “skip to content” link to allow users to skip directly to main content area
* Ensure all functions can be performed by website visitors with limited mobility
  * To test a website for users with limited mobility, focus on keyboard navigation, ensure sufficient color contrast, check for proper alt text, and verify that all elements are accessible via keyboard and can be zoomed without losing functionality

## Reporting

* Provide contact information for users to report accessibility issues that is easy to find
* Include a web accessibility statement on your website

## Responsiveness

* Ensure your website is responsive
* Ensure that users can view with either screen orientation

## Text

* Ensure that when website visitors adjust text spacing, there is no loss in functionality
* Ensure that text can be resized to 200% without loss of content or function
* Ensure that images of text are not used unless necessary
* Provide text alternatives for applicable non-text content

## Tools

* [Accessibility Checker](https://www.accessibilitychecker.org/)
* Figma Plugin [Stark](https://www.getstark.co/)
* WebAim [Web Accessibility Evaluation Tool](https://wave.webaim.org/)
* WebAim [Contrast checker](https://webaim.org/resources/contrastchecker/)

## User Input

* Make sure that there is no “time-out” without user acknowledgment
* Make sues that users can request more time and won’t lose session data by doing it up to 20 hours

## User Testing

* Conduct user testing to find accessibility issues

## Appendix

* Tab key:
  * Moves the focus forward through interactive page elements like links, buttons, and form fields.
* Shift + Tab:
  * Moves the focus backward through interactive page elements.
* Enter key/Spacebar:
  * Activates the focused element, simulating a mouse click, for buttons, links, or form fields.
* Arrow keys:
  * Navigates within components like dropdown menus or groups of radio buttons.
* Esc key:
  * Often used to close modal windows, dropdowns, or dialogues, allowing you to back out of current interactions.
* Other Keyboard Shortcuts:
  * Windows logo key + U: Opens the Ease of Access Center.
  * Alt + Tab: Swaps between open apps.
  * Control+ or Cmd+ C/Copy, X/Cut, V/Paste, Z/Undo, Y/Redo, etc.: Standard text editing shortcuts.
  * Ctrl + F: opens navigation pane in Word
