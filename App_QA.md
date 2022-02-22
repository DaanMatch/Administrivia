# App Testing Quality Assurance

Quality assurance is an important step in the software development lifecycle that ensures users get a fast, seamless and bug free user experience when interacting with our software, web app or mobile app.

The purpose of this checklist is to provide a method of validation for developers at DaanMatch to assist with meeting the minimum requirements of the deliverable.

## Validation Testing

- [] Check all  web pages contain valid XHTML markup. Correct any errors and take any warnings under consideration.
- [] Make sure that all style and display elements are removed from HTML pages and contained within CSS.
- [] Follow hyperlinks to make sure that they are not broken and that they lead to the desired result.
- [] Verify that all internal hyperlinks are relative and not absolute.
- [] Make sure that you have no orphan or dead-end web pages so that users always have a clear navigation path through your site.
- [] Check text for spelling and grammar errors and for any inaccurate or out-of-date information.

## Browser and Device Testing

- [] Test the website's appearance and functionality on multiple browsers, including, at a minimum, Internet Explorer, Firefox, Chrome and Safari, and on multiple versions of those browsers.
- [] Test the website with a variety of displays and screen resolutions, using a variety of devices (including desktops, laptops, tablets and smartphones) and on a variety of operating systems (including Windows, Mac, Linux, Android and iOS).

## Input Testing

- [] Verify that all "optional" or "required" fields are behaving as desired.
- [] Verify that alphanumeric fields can properly handle a wide range of correct and incorrect data, including empty data, invalid symbols and characters, and numbers that are negative or out of range.
- [] Verify that date fields accept proper input, that leap years are properly handled and that any discrepancies between calendars (if relevant) are correctly resolved.
- [] Make sure that extremely long or precise inputs are handled and saved correctly, down to the desired level of accuracy.

## Performance and Bug Testing

- [] Check that data is being saved and retrieved correctly when provided by the user.
- [] Verify that the website behaves correctly when the user deletes their cookies during or after their visit.
- [] Check that web pages are loading and data is retrieved quickly enough, and stress test the website's performance during moderate, heavy and peak demand times.
- [] Make sure that the website is not susceptible to attacks such as SQL injections or brute force attacks, and test the website under a simulated denial-of-service attack.
- [] Make sure that sensitive data, cookies and passwords are encrypted properly, and use the HTTPS protocol on pages with sensitive information.

## Accessibility Testing

- [] Verify that all website images are visible and are the appropriate dimensions and resolutions.
- [] Check that alternatives to audio and visual content, if appropriate, are available for users with hearing or sight issues.
- [] Make sure that your color choices provide enough contrast between different page elements in order to follow good design practices and assist users with sight difficulties or colorblind users.

## Regressions

Use automated regression tests to notify you when an update to the app will break a feature that used to work.
