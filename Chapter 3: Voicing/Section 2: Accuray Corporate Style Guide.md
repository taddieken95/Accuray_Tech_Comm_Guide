# Corporate Style Guidelines

## Accuray Style Guideline Overview

> This style guide establishes the standards through which Accuray employees should follow when producing Accuray documentation. This style guide should be followed with particular accuracy when creating customer-facing documentation (such as a user manual) or any other documentation that is not solely for internal use (such as legal documentation).

When writing about any Accuray product, state the entire name of the product on first mention and use lead caps for each word of the proper name. You are allowed to shorten the product name thereafter. Italicize the product name after the first use. For example, if you are introducing the CyberKnife® Treatment Delivery System you want to write out the full name on first reference. Upon subsequent mentions, you many refer to it as the CyberKnife System. Please note that the word *System* remains capitalized because it is part of the brand name. This rule applies to all product names. When referring to Accuray, the company, state Accuray Incorporated or Accuray. It should never be abbreviated to Accuray, Inc.

### Branding
Use a superscripted TM or ® for products when mentioned in the title and at first mention on the page.

Individual portions of the name should not be translated from English to another language. For example, the InCiseTM Multileaf Collimator is the product name and should be used “as is”; neither “multileaf” nor “collimator” should be translated into another language.

When referencing InciseTM 2 Multileaf Collimator, InCise is trademarked only. You do not need to insert a superscripted TM at the second mention of InCise in a document when referring to both InCise and InCise 2.

After you introduce a product, italicize all terms before the TM or ® upon subsequent mentions in the documentation.

### Typography
Accuray uses Avenir as its primary typeface. If Avenir is not available to you, use Arial.

## General Writing Tools
When in doubt, follow the hierarchy of style guides (Accuray style guides, *Microsoft Manual of Style*, AP Stylebook). Follow the list below to ensure consistency:
* Minimize the use of ampersands (exception example: R&D). Spell out “and” in sentences.
* Avoid use of contractions.
* Avoid use of Latin (e.g., i.e., etcetera).
* Keep punctuation within quotation marks. Ex.: He said, "XXX," and then...
* Use the number itself when indicating percentages. For all other purposes, spell out the number in text for numerals below 10 and use the number itself beginning with 10 and greater. If the number is the start of a sentence, spell out the number in text.
(Ex. 20 percent, option nine out of 10, ten percent of cases)
* Include aspace between measurements: 30 Gy, 25 cGy, 40 cm, 6 ft., 10:00 A.M.
* Hyphenate two words combined to make an adjective (Ex.: image-guided radiation therapy).

### Voice and Mood
Avoid the passive voice except when necessary to avoid a wordy or awkward construction; when the subject is unknown or not the focus of the sentence; or in error messages and troubleshooters when the user is the subject and might feel blamed for the error if the active voice is used. The passive voice is more often used and acceptable in programmer documentation.

Use the indicative mood to express general information such as facts, assertion, or explanations. Use this mood in most documentation.
* Ex.: Style sheets are powerful tools for formatting complex documents.

Use the imperative mood for procedures and direct instructions. The subject “you” is generally understood. Use only the present tense with the imperative mood.
* Ex.: Type a file name and click **OK**.

### Parallelism
Items in list should be parallel to each other in structure. For example, if the first item in a list begins with an imperative verb, all the items in the list should begin with an imperative verb.

Ex.: There are several ways to open documents in Windows. You can:
* Open your document from within the program that you used to create it.
* Use the **Search** command on the **Start** menu to locate the document, and then open it.
* Double-click the document icon to open a document.

Likewise, procedure steps should be written in parallel style.

Ex.: To reset a Treatment Machine:
1. Open the **System Administration** application.
2. Click the **OIS** tab.
3. Select the desired server and click the **refresh** icon.
4. Select the treatment machine the server is associated with and click **OK**.

### Word Choice
The best documentation conveys information in a concise manner. The following guidelines are intended to eliminate confusion and redundancy.
* Use the phrase "because of" instead of "due to."
* Use "enables" instead of "allows."
* Use "may" when referring to permissions. Ex.: If OIS is enabled (signaled by **Yes**), you may skip ahead to *Server Configuration*.
* Use "might" when referring to uncertain possibilities. Ex.: Selecting the wrong patient record can result in treatment errors, which might lead to serious injury.

### Alert Words
Use the following words and symbols to signal important information:

| Icon     | Word        | Description  |
| ------------- |:-------------:|-----|
| <img src="https://icon-library.net/images/warning-icon/warning-icon-5.jpg" alt="Warning Icon" width="100"/>| **WARNING** | Improper use will likely affect safety.
| <img src="https://image.flaticon.com/icons/svg/66/66872.svg" alt="Caution Icon" width="100"/>| **CAUTION**     |   Improper use will result in machine damage.

### Acronyms
If you use an acronym to represent a phrase that you plan to include multiple times in your document, you should first write the complete phrase followed by the acronym in parenthesis; you can then refer to the acronym throughout the rest of your document. For example, if you plan to write about stereotactic body radiation therapy, include the full phrase followed by (SBRT) before you begin using the acronym.

### Important Terms
|Abbreviation  | Definition |
|--------------|:------------|
|DICOM         |Digital Imaging and Communications in Medicine
|DVH           |Dose volume histogram
|FFP           |Feet first prone
|FFS           |Feet first supine
|Gy            |Gray. The interanational system unit of absorbed dose of radiation (Gy), 1 Gy = J/kg = 100 rad.
|HFP           |Head first prone
|HFS           |Head first supine
|IMRT          |Intensity modulated radiotherapy
|KVCT          |Kilovoltage computed tomography
|Linac         |Linear accelerator
|MLC           |Multileaf collimator
|MRI           |Magnetic resonance imaging
|ROI           |Region of interest
|RT            |Radiotherapy

In general, avoid using acronyms in place of product names. If the acronym is trademarked (TQA [Total Quality Assurance] Software), it is acceptable to use the acronym in documentation.

### Image Convention
It is not necessary to label an image if the preceding text sufficiently describes it or if the image is self-explanatory.

## Miscellaneous Information
The following files must go in a translation package to our vendors:
* Any conditional text that needs to be called out
*	ENG Front Matter
*	ENG Source Files
*	ENG Image Files
*	ENG Cover Source Files 
*	ENG Cover Source Image Files
*	ENG PDF
*	ENG Covers PDF (with and without bleeds)
*	ENG Metadata (if applicable)
*	PDF Redlines of Changes between Revisions (if applicable)

The files that Accuray sends (xml, fm, docx) must match the final released PDF that is sent to the vendors.

> To continue to the next section of this chapter on Accuray terminology, click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%203:%20Voicing/Section%203:%20Accuray%20Terms.md). Otherwise, click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%203:%20Voicing/READme.md) to return to the chapter overview.
