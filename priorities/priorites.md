

## 1.1 Text Alternatives: Provide text alternatives for any non-text content

### 1.1.1 Non-text Content (A)

Failures and issues:

* Using CSS to include images that convey important information. (ex. uses background images to provide icons against a list of items to indicate what they are)
* Having a text alternative that does not include information that is conveyed by color differences in the image.
* Not updating text alternatives when changes to non-text content occur (ex. charts text alt are not updated at the same time as chart)
* Using text alternatives that are not alternatives (e.g., filenames or placeholder text) 
* Not marking up decorative images in HTML in a way that allows assistive technology to ignore them (Ex. decorative images that have no alt attribute and no role attribute)
* `applet` contains a text equivalent in the `alt` attribute of the `applet`.
* Providing a text alternative that is not null (e.g., alt="spacer" or alt="image") for images that should be ignored by assistive technology
* Alt text for all `img` elements is not placeholder text unless author has confirmed it is correct. 
* Omitting the alt attribute or text alternative on img elements, area elements, and input elements of type "image"
* Using text look-alikes to represent text without providing a text alternative
* `applet` contains a text equivalent in the body of the `applet`.
* All `area` elements have an `alt` attribute.
* Alt text for all `area` elements identifies the link destination.
* `area` link to sound file must have text transcript.
* Alt text for all `area` elements contains all non decorative text in the image area.
* All `embed` elements have an associated `noembed` element that contains a text equivalent to the `embed` element.
* All `img` elements have an `alt` attribute.
* Alt text is not the same as the filename unless author has confirmed it is correct.
* Image Alt text is short.
* Alt text for all `img` elements used as source anchors is not empty when there is no other text in the anchor.
* A long description is used for each `img` element that does not have Alt text conveying the same information as the image.
* Alt text for all `img` elements is the empty string ("") if the image is decorative.
* Alt text for all `img` elements that are not used as source anchors conveys the same information as the image.
*  `title` attribute for all `img` elements is absent or the empty string ("") if the image is decorative.
* All `input` elements with a `type` attribute value of "image" have an `alt` attribute.
* Alt text for all `input` elements with a `type` attribute value of "image" identifies the purpose or function of the image.
* Alt text for all `input` elements with a `type` attribute value of "image" is less than 100 characters (English) or the user has confirmed that the Alt text is as short as possible.
* Image used in `input` element * Alt text should not be placeholder text.
* Alt text for all `input` elements with a `type` attribute value of "image" contains all non decorative text in the image.
* All `input` elements, except those with a `type` attribute value of "image", do not have an `alt` attribute.
* All `objects` contain a text equivalent of the `object`.

## 1.2 Time-based Media: Provide alternatives for time-based media.

### 1.2.1 Audio-only and Video-only (Pre-recorded) (A)

* Sound file require a text transcript.
* Links to multimedia require a text transcript.
* Links to multimedia have a link to text alternative.

### 1.2.2 Captions (Pre-recorded) (A)

* Captions omitting some dialogue or important sound effects (This describes a failure condition for all techniques involving captions. If the "caption" does not include all of the dialogue (either verbatim or in essence) as well as all important sounds then the 'Captions' are not real captions
* Providing synchronized media without captions when the synchronized media presents more information than is presented on the page 
* Not labeling a synchronized media alternative to text as an alternative (ex. synchronized media version is provided elsewhere on the page and is not clearly labeled with the part of the text for which it is a substitute)
 

### 1.2.3 Audio Description or Media Alternative (Pre-recorded) (A)

* `object` link to multimedia file require equivalent alternatives (e.g., captions or auditory descriptions of the visual track).
* `object` may require a long description.

### 1.2.4 Captions (Live) (AA)

N/A

### 1.2.5 Audio Description (Pre-recorded) (AA)


## 1.3 Adaptable: Create content that can be presented in different ways (for example simpler layout) without losing information or structure.

### 1.3.1 Info and Relationships (A)

* Using changes in text presentation to convey information without using the appropriate markup or text. (A change in the appearance of text conveys meaning without using appropriate semantic markup. This failure also applies to images of text that are not enclosed in the appropriate semantic markup.) 
* Using CSS to style the p element to look like a heading. 
* Using CSS to visually emphasize a phrase or word without conveying that emphasis semantically 
* Using white space characters to create multiple columns in plain text content (Ex. The document for data or information presented in columnar format and the columns are created using white space characters to lay out the information)
* Using white space characters to format tables in plain text content
* Using structural markup in a way that does not represent relationships in the content (Example: Using heading elements for presentational, visual effect. Using blockquote elements to provide additional indentation. Using the fieldset and legend elements to give a border to text)
* Using th elements, caption elements, or non-empty summary attributes in layout tables * using structural (or semantic) markup only for presentation. 
* Using the <pre> element to markup tabular information
* Inserting non-decorative content by using :before and :after pseudo-elements and the 'content' property in CSS.
* Incorrectly associating table headers and content via the headers and id attributes 
* Not correctly marking up table headers
* Use of role presentation on content which conveys semantic information (Ex.  If an element which conveys information, structure, or relationships through its semantic markup has the attribute role="presentation".) 
* Table markup are used for all tabular information
* All visual lists are marked.
* Unicode right-to-left marks or left-to-right marks are used whenever the HTML bidirectional algorithm produces undesirable results.
* All changes in text direction are marked using the `dir` attribute.
* Table captions identify the table.
* All radio button groups are marked using `fieldset` and `legend` elements.
* All checkbox groups are marked using `fieldset` and `legend` elements.
* All `input` elements, `type` of "text", have an explicitly associated label.
* All `input` elements, `type` of "password", have an explicitly associated `label`.
* All `input` elements, `type` of "checkbox", have an explicitly associated `label`.
* All `input` elements, `type` of "file", have an explicitly associated `label`.
* All `input` elements, `type` of "radio", have an explicitly associated `label`.
* All `input` elements, `type` of "password", have a label that is positioned close to the control.
* All `input` elements, `type` of "checkbox", have a label that is positioned close to the control.
* All `input` elements, `type` of "file", have a label that is positioned close to the control.
* All `input` elements, `type` of "radio", have a label that is positioned close to the control.
* All `input` elements, `type` of "radio", have a `label` containing text.
* All `input` elements, `type` of "checkbox", have a `label` containing text.
* All `input` elements, `type` of "password", have a `label` containing text.
* All `input` elements, `type` of "text", have a label that is positioned close to the control.
* All `input` elements, `type` of "text", have a `label` containing text.
* All `input` elements, `type` of "file", have a `label` containing text.
* All `p` elements are not used as headers.
* `pre` element should not be used to create tabular layout.
* All `select` elements have an explicitly associated `label`.
* All `select` elements have a label that contains text.
* All `select` elements have a label that is positioned close to the control.
* All complex data tables have a summary.
* All data `table` summaries contain text.
* All layout `tables` have an empty `summary` attribute or no `summary` attribute.
* All layout tables do not contain `caption` elements.
* All data tables contain `th` elements.
* All layout tables do not contain `th` elements.
* All data tables contain a `caption` unless the table is identified within the document.
* All data table summaries describe navigation and structure of the table.
* Use `thead` to group repeated table headers, `tfoot` for repeated table footers, and `tbody` for other groups of rows.
* Use `colgroup` and `col` elements to group columns.
* Table summaries do not duplicate the table captions.
* Data tables that contain both row and column headers use the `scope` attribute to identify cells.
* Data tables that contain more than one row/column of headers use the `id` and `headers` attributes to identify cells.
* All `textarea` elements have an explicitly associated label.
* All `textarea` elements have a label that is positioned close to control.
* All `textarea` elements have a `label` containing text.

### 1.3.2 Meaningful Sequence (A)

* Using white space characters to format tables in plain text content (the same for Success criteria 1.3.1)
* Using white space characters to control spacing within a word (Ex. Adding white space in the middle of a word-non-standard spacing between characters)
* Using an HTML layout table that does not make sense when linearized. All layout `tables` should make sense when linearized. (Reading order does not match any meaningful sequence conveyed through presentation)
* Changing the meaning of content by positioning information with CSS 

### 1.3.3 Sensory Characteristics (A) 

* Content does not restrict its view and operation to a single display orientation, such as portrait or landscape, unless a specific display orientation is essential.
* All text references do not use shape, size, or relative position alone.(Ex. o go to next page, press the button to the right. To go back to previous page, press the button to the left. Press the square button)
* Using a graphical symbol alone to convey information (Ex. A graphical symbol may be an image, an image of text or a pictorial or decorative character symbol (glyph) which imparts information nonverbally. Examples of graphical symbols include an image of a red circle with a line through it, a "smiley" face, or a glyph which represents a check mark, arrow, or other symbol but is not the character with that meaning. 
* Assistive technology users may have difficulty determining the meaning of the graphical symbol)

### 1.3.4 Orientation (AA) (Added in WCAG 2.1)

* Locking the orientation to landscape or portrait view * any controls in the content, user agent, operating system, or device that restrict or allow orientation changes (Ex. When the device is turned to landscape view, the content appears sideways to the user.) 

### 1.3.5 Identify Input Purpose (AA) (Added in WCAG 2.1)

* N/A

## 1.4 Distinguishable: Make it easier for users to see and hear content including separating foreground from background.

### 1.4.1 Use of Color (A)

* Creating links that are not visually evident without color vision (Ex. The links are styled so that they do not have underlines and are very similar in color to the body text.)
* `applet` should not use color alone.
* Identifying required or error fields using color differences only
* All text colors or no text colors are set.
* For all `img` elements, text does not refer to the image by color alone.
* The luminosity contrast ratio between text and background color in all images is at least 5:1.
* `input` should not use color alone.
* `object` must not use color alone.
* Color alone should not be used in the `script`.

### 1.4.2 Audio Control (A)

* Playing a sound longer than 3 seconds where there is no mechanism to turn it off 
* Absence of a way to pause or stop an HTML5 media element that autoplays 

### 1.4.3 Contrast (Minimum) (AA)

* Visited link text colour must contrast sufficiently with its background colour.
* Active link text colour must contrast sufficiently with its background colour.
* Selected link text colour must contrast sufficiently with its background colour.
* Link text colour must contrast sufficiently with its background colour.
* Provide sufficient contrast between text and background colours.
* Using background images that do not provide sufficient contrast with foreground text (or images of text)

### 1.4.4 Resize text (AA)

* When resizing visually rendered text up to 200 percent causes the text, image or controls to be clipped, truncated or obscured.
* Text-based form controls do not resize when visually rendered text is resized up to 200%
* Incorrect use of viewport units to resize text. 
* `b` (bold) element is not used.
* `basefont` must not be used.
* `font` must not be used.
* `i` (italic) element is not used.

### 1.4.5 Images of Text (AA)

* Alt text for all `img` elements contains all text in the image unless the image text is decorative or appears elsewhere in the document.

### 1.4.10 Reflow (AA) (Added in 2.1) Content can be presented without loss of information or functionality, and without requiring scrolling in two dimensions for: 

* Vertical scrolling content at a width equivalent to 320 CSS pixels;
* Horizontal scrolling content at a height equivalent to 256 CSS pixels;
* Except for parts of the content which require two-dimensional layout for usage or meaning.
* Using fixed sized containers and fixed position content (CSS)
* (HTML) Using preformatted text or excluding preformatting text as an exception to no two dimensional scrolling.

### 1.4.11 Non-text Contrast (AA) (Added in 2.1)Non-text Contrast. The visual presentation of the following have a contrast ratio of at least 3:1 against adjacent color(s): 

* User Interface Components: Visual information required to identify user interface components and states, except for inactive components or where the appearance of the component is determined by the user agent and not modified by the author;
* Graphical Objects: Parts of graphics required to understand the content, except when a particular presentation of graphics is essential to the information being conveyed.
* Styling element outlines and borders in a way that removes or renders non-visible the visual focus indicator 

### 1.4.12 Text Spacing (AA) (Added in 2.1) Text Spacing. In content implemented using markup languages that support the following text style properties, no loss of content or functionality occurs by setting all of the following and by changing no other style property: 

* Line height (line spacing) to at least 1.5 times the font size;
* Spacing following paragraphs to at least 2 times the font size;
* Letter spacing (tracking) to at least 0.12 times the font size;
* Word spacing to at least 0.16 times the font size.
* Exception: Human languages and scripts that do not make use of one or more of these text style properties in written text can conform using only the properties that exist for that combination of language and script.

### 1.4.13 Content on Hover or Focus (AA) (Added in 2.1)

* Where receiving and then removing pointer hover or keyboard focus triggers additional content to become visible and then hidden, the following are true: 
* Dismissible: A mechanism is available to dismiss the additional content without moving pointer hover or keyboard focus, unless the additional content communicates an input error or does not obscure or replace other content;
* Hoverable: If pointer hover can trigger the additional content, then the pointer can be moved over the additional content without the additional content disappearing;
* Persistent: The additional content remains visible until the hover or focus trigger is removed, the user dismisses it, or its information is no longer valid.
* Content shown on hover not being hoverable 
* Failure to make content dismissable without moving pointer hover or keyboard focus
* Failure to meet by content on hover or focus not remaining visible until dismissed or invalid

## 2.1 Keyboard Accessible: Make all functionality available from a keyboard.

### 2.1.1 Keyboard (A)

* Using script to remove focus when focus is received 
* Using only pointing-device-specific event handlers (including gesture) for a function: 
* All `ondblclick` event handlers have corresponding keyboard-specific functions.
* All `onmousedown` event handlers have an associated `onkeydown` event handler.
* All `onmousemove` event handlers have corresponding keyboard-specific functions.
* All `onmouseout` event handlers have an associated `onblur` event handler.
* All `onmouseover` event handlers have an associated `onfocus` event handler.
* All `onmouseup` event handlers have an associated `onkeyup` event handler.
* `applet` user interface must be accessible.
* `object` user interface must be accessible * (codebase).

### 2.1.2 No Keyboard Trap (A)

* Combining multiple content formats in a way that traps users inside one format type (Ex. the keyboard focus should not be "trapped" and it is possible to move keyboard focus out of the plug-in content without closing the user agent or restarting the system.)
* `applet` provides a keyboard mechanism to return focus to the parent window.
* `embed` provides a keyboard mechanism to return focus to the parent window.
* `object` provides a keyboard mechanism to return focus to the parent window.

### 2.1.4 Character Key Shortcuts (A) (Added in 2.1). If a keyboard shortcut is implemented in content using only letter (including upper* and lower-case letters), punctuation, number, or symbol characters, then at least one of the following is true: 

* Turn off: A mechanism is available to turn the shortcut off;
* Remap: A mechanism is available to remap the shortcut to include one or more non-printable keyboard keys (e.g., Ctrl, Alt);
* Active only on focus: The keyboard shortcut for a user interface component is only active when that component has focus.
* Failure due to due to a webpage or web app that includes single-key shortcuts not including a control that allows users to turn the shortcuts off or a control that allows users to change the shortcuts to key combinations that include keys that are not upper or lower-case letters, punctuation, number, or symbol characters.

## 2.2 Enough Time: Provide users enough time to read and use content.

### 2.2.1 Timing Adjustable (A)

* Meta redirect with a time limit 
* Using meta refresh to reload the page 
* Using server-side techniques to automatically redirect pages after a time-out 

### 2.2.2 Pause, Stop, Hide (A)

* Including scrolling content where movement is not essential to the activity without also including a mechanism to pause and restart the content 
* Using the blink element:
* `blink` element should not used.
* Using a script that causes a blink effect without a mechanism to stop the blinking at 5 seconds or less 
* `marquee` element should not be used.
* Auto-redirect must not be used.
* An object or applet, such as Java or Flash, that has blinking content without a mechanism to pause the content that blinks for more than five seconds 

## 2.3 Seizures: Do not design content in a way that is known to cause seizures.

### 2.3.1 Three Flashes or Below Threshold (A)

* `applets` cause screen flicker.
* All `img` elements have associated images that do not flicker.
* All `objects` do not flicker.
* `script` should not cause screen flicker.

## 2.4 Navigable: Provide ways to help users navigate, find content, and determine where they are.

### 2.4.1 Bypass Blocks (A)

* A "skip to content" link appears on all pages with blocks of material prior to the main document.
* All groups of links with a related purpose should be marked.
* All `frames` have a `title` attribute.
* All `frame` `titles` identify the purpose or function of the `frame`.
* ASCII art should have a skipover link.

### 2.4.2 Page Titled (A)

* The title of a Web page not identifying the contents:
* `title` contains text.
* `title` is short.
* `title` is not placeholder text.
* `title` describes the document.

### 2.4.3 Focus Order (A)

* Using tabindex to create a tab order that does not preserve meaning and operability (When the values of the tabindex attribute are assigned in a different order than the relationships and sequences in the content, the tab order no longer follows the relationships and sequences in the content. )
* Using dialogs or menus that are not adjacent to their trigger control in the sequential navigation order

### 2.4.4 Link Purpose (In Context) (A)

* Not providing an accessible name for link contains only non-text content.
* Not providing an accessible name for non-text content has been implemented in a way that it can be ignored by assistive technologies, such as using role="presentation" or alt="" . 
* Not providing an accessible name for link does not have an accessible name provided in another way such as aria-label or aria-labelledby. 
* Providing link context only in content that is not related to the link. 
* Link text is meaningful when read out of context.
* Suspicious link text.
* Each source anchor contains text.
* All source anchors contain text that identifies the link destination.

### 2.4.5 Multiple Ways (AA)

* Should be more than one way is available to locate a Web page within a set of Web pages except where the Web Page is the result of, or a step in, a process.

### 2.4.6 Headings and Labels (AA)

* The header following an `h1` is `h1` or `h2`.
* All `h1` elements are not used for formatting.
* The header following an `h2` is `h1`, `h2` or `h3`.
* All `h2` elements are not used for formatting.
* The header following an `h3` is `h1`, `h2`, `h3` or `h4`.
* All `h3` elements are not used for formatting.
* The header following an `h4` is `h1`, `h2`, `h3`, `h4` or `h5`.
* All `h4` elements are not used for formatting.
* The header following an `h5` is `h6` or any header less than `h6`.
* All `h5` elements are not used for formatting.
* All `h6` elements are not used for formatting.

### 2.4.7 Focus Visible (AA)

* Using script to remove focus when focus is received 
* Styling element outlines and borders in a way that removes or renders non-visible the visual focus indicator (Ex. The focus indicator is turned off with CSS. The outline of elements is visually similar to the focus indicator. Elements have a border that occludes the focus indicator)

## 2.5 (Added in 2.1)Input Modalities.Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.1 (Added in 2.1) Pointer Gestures (A).All functionality that uses multipoint or path-based gestures for operation can be operated with a single pointer without a path-based gesture, unless a multipoint or path-based gesture is essential.

* Failure: Functionality can be operated by pointer input but not with single-point activation alone.

### 2.5.2 Pointer Cancellation (A) (Added in 2.1). For functionality that can be operated using a single pointer, at least one of the following is true: 

* No Down-Event: The down-event of the pointer is not used to execute any part of the function;
* Abort or Undo: Completion of the function is on the up-event, and a mechanism is available to abort the function before completion or to undo the function after completion;
* Up Reversal: The up-event reverses any outcome of the preceding down-event;
* Essential: Completing the function on the down-event is essential.
* Failure: due to activating a button on initial touch location rather than the final touch location.

### 2.5.3 Label in Name (A) (Added in 2.1).. For user interface components with labels that include text or images of text, the name contains the text that is presented visually

* The accessible name not containing the visible label text
* Mismatch of visible button text and accessible name supplied via aria-label
* Invisible link text disrupts visible label text string in accessible name
* Input with a hidden label carrying text that differs from the input's value attribute 
* Accessible name contains the visible label text, but the words of the visible label are not in the same order as they are in the visible label text
* Accessible name contains the visible label text, but one or more other words are interspersed in the label

### 2.5.4 Motion Actuation (A) (Added in 2.1). Functionality that can be operated by device motion or user motion can also be operated by user interface components and responding to the motion can be disabled to prevent accidental actuation, except when: 

* Supported Interface: The motion is used to operate functionality through an accessibility supported interface;
* Essential: The motion is essential for the function and doing so would invalidate the activity.
* Functionality that can only be activated via devicemotion events (e.g., shaking or tilting)
* An inability to disable motion actuation
* Disrupting or disabling system level features which allow the user to disable motion actuation.

## 3.1 Readable: Make text content readable and understandable.

### 3.1.1 Language of Page (A)

* Document should have valid language code.
* Reading order direction is marked using the html element's `dir` attribute if the document's primary language is read right to left.

### 3.1.2 Language Parts (AA)

* Words outside the primary language are not marked

## 3.2 Predictable: Make Web pages appear and operate in predictable ways.

### 3.2.1 On Focus (A)

* Using script to remove focus when focus is received 
* Loading the web page does not cause a new window to open.

### 3.2.2 On Input (A)

* Automatically submitting a form and presenting new content without prior warning when the last field in the form is given a value 
* Change of context occurs only by user activation unless a warning is provided.
* Launching a new window without prior warning when the selection of a radio button, check box or select list is changed 
* `area` should not open new window without warning.
* All `select` elements do not cause an extreme change in context.

### 3.2.3 Consistent Navigation (AA)

* Presenting navigation links in a different relative order on different pages 
* Repeated components do not appear in the same relative order each time they appear.
* The tab order specified by `tabindex` attributes follows a logical order.
* Repeated blocks of content do not appear in the same `frame` within the `frameset`.

### 3.2.4 Consistent Identification (AA)

* Using two different labels for the same function on different Web pages within a set of Web pages. (Ex. Serch, Find * not consistent)
* `blockquote` must not be used for indentation.
* Use the `blockquote` element to mark up block quotations.
* List items must not be used to format text.

## 3.3 Input Assistance: Help users avoid and correct mistakes.

### 3.3.1 Error Identification (A)

* Not providing any techniques to meet this criteria, like:
* No mechanism to jump to errors
* No text descriptions to identify required fields not completed if a form contains fields for which information from the user is mandatory.
* All form submission error messages should identify any empty required fields.

### 3.3.2 Labels or Instructions (A)

* Visually formatting a set of phone number fields but not including a text label 
* Each `input` element has only one associated `label`.
* All `form` fields that are required are indicated to the user as required.
* Each label associated with an `input` element contains text.
* Each label describes its asssociated `input` element.
* All `input` elements, `type` of "file", have a `label` that describes the purpose or function of the control.
* All `input` elements, `type` of "password", have a `label` that describes the purpose or function of the control.
* All `input` elements, `type` of "text", have a `label` that describes the purpose or function of the control.
* All `input` elements, `type` of "checkbox", have a `label` that describes the purpose or function of the control.
* All `input` elements, `type` of "radio", have a `label` that describes the purpose or function of the control.
* All `select` elements have a label that describes the purpose or function of the control.

### 3.3.3 Error Suggestion (AA)

* All form submission error messages should provide assistance in correcting the error.

### 3.3.4 Error Prevention (Legal, Financial, Data) (AA)

* Form submission data is presented to the user before final acceptance for all irreversable transactions.
* Information deleted using a web page can be recovered.

## 4.1 Compatible: Maximize compatibility with current and future user agents, including assistive technologies.

### 4.1.1 Parsing (A)

* Incorrect use of start and end tags or attribute markup
* `id` attributes must be unique (not duplicated)

### 4.1.2 Name, Role, Value (A)

* Using script to make div or span a user interface control in HTML without providing a role for the control 
* Implementing custom controls that do not use an accessibility API for the technology, or do so incompletely 
* Not updating text alternatives when changes to non-text content occur
* A user interface control not having a programmatically determined name (each element should have a programmatically determined name using one of the following ways: 
* the text label or labels are programmatically associated with the control element via the aria-labelledby attribute (each id given as a value in the aria-labelledby attribute matches the id of the text label element).
* The focus state of a user interface component not being programmatically determinable or no notification of change of focus state available 
* Not providing names for each part of a multi-part form field, such as a US telephone number (A name does not necessarily have to be visible, but is visible to assistive technologies)
* Not providing an accessible name for an image which is the only content in a link 

### 4.1.3 Status Messages (AA) (Added in 2.1). In content implemented using markup languages, status messages can be programmatically determined through role or properties such that they can be presented to the user by assistive technologies without receiving focus.

* Using role="alert" or aria-live="assertive" on content which is not important and time-sensitive 
* Using a visibilitychange event to hide or display a document without switching the document's live regions between active and inactive
