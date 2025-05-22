# Accessibility Checklist

An accessibility checklist is a tool used to ensure that digital content and interfaces meet established accessibility standards, such as the Web Content Accessibility Guidelines (WCAG). It typically covers key areas like perceivability, operability, understandability, and robustness, providing specific criteria to evaluate and improve accessibility. By following an accessibility checklist, developers and designers can identify and address potential barriers, making their products more inclusive and user-friendly for people with disabilities

## Code

* Use unique title for each page or view
* Make sure that viewport zoom is not disabled
* Use landmark for important content

## Contrast

* Ensure a high contrast between text sections and their backgrounds with a ratio of at least 4.5:1
* You cannot round a contrast ratio up to 4.5:1
* Ensure that information conveyed by color is visually evident without color
  `<img width="350" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://www.emailonacid.com/wp-content/uploads/2021/08/image3.png">`

## Documents

* All linked documents not in HTML format, such as PDFs, presentations, spreadsheets, and Word documents, meet their type’s basic accessibility requirements
* PDFs need to be tagged in the valid reading order for accessibility.

## Errors

* Ensure error messages are specific and provide guidance

## Form Field Labels

* Place form field labels next to the text fields. This allows users who use assistive technologies to interact with the form
* Optimize color contrast and text readability for the visually impaired

## Labels

* Use headings correctly to organize the structure of content
* Unique page titles
* Use Aria role tags for each element
* Ensure that web elements don’t change when they get input

## Links

* If the links change color on hover or focus each of the colors in these states must also have at least a 4.5:1 contrast ratio difference with the background
* links should have a text description that can be read by a screen reader

## Menus and Buttons

* Ensure that menus and buttons appear in the same order and presentation throughout the site
* Ensure menus, icons, and buttons appear consistently

## Multimedia

* Provide transcript for video and audio
* Provide captions for videos with audio
* Provide controls when auto-playing is enabled
* Ensure that there are no seizures inducing content
* Provide users with audio description for video content
* Include alt text for images

## Navigation

* Ability to use keyboard to navigate
* Ensure that users can navigate your website using keyboard shortcuts
* Provide a “skip to content” link to allow users to skip directly to main content area

## Orientation

* Ensure that users can view with either screen orientation

## Reporting

* Provide contact information for users to report accessibility issues that is easy to find
* Include a web accessibility statement on your website

## Responsiveness

* Ensure your website is responsive

## Text

* Ensure that when website visitors adjust text spacing, there is no loss in functionality
* Ensure that text can be resized to 200% without loss of content or function
* Ensure that images of text are not used unless necessary

## Tools

* [Accessibility Checker](https://www.accessibilitychecker.org/)
* Figma Plugin [Stark](https://www.getstark.co/)
* WebAim [Web Accessibility Evaluation Tool](https://wave.webaim.org/)
* WebAim [Contrast checker](https://webaim.org/resources/contrastchecker/)

## User Input

* Make sure that there is no “time-out” without user acknowledgment
* Make sues that users can request more time and won’t lose session data by doing it

## User Testing

* Conduct user testing to find accessibility issues
