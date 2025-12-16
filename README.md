# HTML-Accessibility-Fixes
#  HTML Accessibility & Semantic Review Portfolio

**Project Status:** Completed and Fully Compliant

**Technologies Used:** HTML5, CSS3, ARIA Standards, Semantic Web Principles

---

##  Context: Demonstrating Code Quality Assurance (QA)

This repository serves as a practical demonstration of my code review expertise, a core skill developed while training and evaluating Large Language Models (LLMs) on platforms like Remotasks. The goal here is to take non-compliant, functionally poor HTML code and refactor it to meet modern **WCAG Accessibility Standards** and **Semantic HTML5 best practices**.

##  The Review Challenge: `broken_form.html`

The original file represents a typical output that fails critical quality checks. Key flaws identified during the review process included:

| Flaw Category | Specific Issue | Impact on User Experience |
| :--- | :--- | :--- |
| **Accessibility (A11y)** | Missing `<label for="...">` attributes for inputs. | Screen readers cannot correctly announce the purpose of the field, making the form unusable for visually impaired users. |
| **Semantic Error** | Using `<br>` tags for layout spacing. | Incorrect separation of concerns; HTML should define structure, not visual spacing (which belongs in CSS). |
| **Input Validation** | No use of HTML5 attributes like `required`. | Forces reliance on JavaScript for simple checks and does not leverage native browser validation features. |
| **Usability** | The submit button was just `<button>Click</button>`. | Poor user experience; button text should clearly describe its action (e.g., "Submit Registration"). |

##  The Solution: `fixed_form.html`

The refactored code (in `fixed_form.html`) demonstrates strict adherence to guidelines and quality control:

1.  **Full Accessibility:** Implemented explicit **`for` and `id`** matching between all labels and inputs.
2.  **Semantic Purity:** Replaced all visual line breaks with standard CSS margins/padding (not shown here, but implied for best practice).
3.  **Enhanced QA:** Added the **`required`** attribute to form fields, validating inputs before submission.
4.  **Professional Clarity:** Updated button text and ensured the HTML document used the `lang="en"` attribute.

---

##  Skills Demonstrated

* **Meticulous Code Review & Debugging**
**Adherence to Complex WCAG/W3C Standards**
* **Semantic HTML5 Architecture**
* **Quality Assurance (QA) for Front-End Code**
* **Adherence to Complex WCAG/W3C Standards**
* **Semantic HTML5 Architecture**
* **Quality Assurance (QA) for Front-End Code**

This project proves my ability to not only write code but critically evaluate it against professional standards, ensuring high-quality outputs for any development environment.
