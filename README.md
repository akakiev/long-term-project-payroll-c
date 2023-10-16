<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Payroll-Management-System using C++

The project has multiple classes and sub-classes with some features within them. Basic operations users can perform via this program project which has such functions: adding new employee record, modifying employee record and deleting record, displaying one or all employee’s record. Besides these, payroll management also allows users to print the salary slip for a particular employee.

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
  TBD-step-1-notes.
-->

## The Project classes:
<p>1. LINES<br />
- LINE_HOR<br />
- LINE_VER<br />
- BOX<br />
- CLEARUP<br />
- CLEARDOWN<br />
<p>2. MENUS<br />
- MAIN_MENU<br />
- EDIT_MENU<br />
- INTRODUCTION<br />
<p>3. EMPLOYEE<br />
- NEW_EMPLOYEE<br />
- MODIFICATION<br />
- DELETION<br />
- DISPLAY<br />
- LIST<br />
- SALARY_SLIP<br />
- ADD_RECORD<br />
- MODIFY_RECORD<br />
- DELETE_RECORD<br />
- LASTCODE<br />
- CODEFOUND<br />
- RECORD<br />
- FOUND_CODE<br />
- DISPLAY_RECORD<br />
- VALID_DATE<br />

## Project Operations:
<p>Addition of New Employee:<br />
This feature is under the public functions of class employee. The information handled in this feature are employee code number, name, address, phone number, joining date (day, month and year), designation, grade and loan.<br />
<p>Modify Employee Record:<br />
This System in C++ asks for employee code from the user for this function to work. Modifications that can be made are the employee code number itself, joining date (day, month and year), name, address, phone number, designation, grade, house allowance and loan given to the employee. Employee’s grades are categorized as A, B, C, D and E.
<p>Delete Employee Record:<br />
Deletion is done of an employee record from Payroll management system project by entering the employee code. A confirmation message is asked stating whether the user really wants to delete the record from the file.<br />
<p>Print Employee Salary Slip:<br />
This feature too asks for the employee code; the employee code has been used to unlock or perform operations in many features of this payroll management system project in C++. This function lists all the months of the year, and asks for date, employee name, designation and grade from the user. To print the salary slip, the user further needs to provide information such as number of days worked in the month by the employee and the number of hours worked over time. The slip enlists basic salary, allowance, deductions and net salary of the employee.<br />
<p>Display Employee Record:<br />
Providing the employee code number, users can access all the provided information related to a particular employee via this function. The employee record information displayed are the ones provided while adding a new employee record.<br />
<p>Display List of Employees:<br />
This feature displays the record of all employees added in file. The records are displayed in a tabular pattern containing information such as code name of the employee, phone number, date of joining, designation, grade and salary.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [TBD-support](TBD-support-link) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 TBD-copyright-holder &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
