# DailyTimeRecord
 A Daily Time Record (DTR) is the process of monitoring and organizing time information. Far from just being a way to monitor the attendance of an employee, having a DTR system allows a company to effectively manage its employees by providing adequate data.
Most companies, even government offices, require duly accomplished DTRs for salary and compensation audits. This is because having an ineffective system for daily time record can disrupt payroll systems, increase paperwork, and impede accurate productivity computation. The benefits of having a DTR System is to give the employee or user the idea in a real time figure manpower count of present, absent or late.

__The application utilizes PHP, XML, XAMPP, and manipulation of SQL data.__

----
Below are the following features implemented in the web application:

* Register: _Inserts the employee information into the database as a registered user._
* Login: _Validates and determines employee type according to logged in user._
* Profile
  * Show Profile: _Displays relevant information about the employee such as job position, hire date, and full name._
  * Update Profile: _Allows for changes in information about the employee account such as password._
* File DTR (Weekly)
  * File through portal: _The employee is able to file their workdays, leave, and as well as specify the work hours in order to compute their compensation accordingly._
  * Upload XML: _The employee can import DTR data from XML into the database._  
* Compute Compensation (Bi-monthly)
* Generate Report (Monthly): _The employee can choose a month they have hours worked and generate a report of their salary computation on the given month if the minimum work hours are met._
* Chatbot: _Creates a client/server session through sockets programming to simulate a chat system. This imitates a conversation between the system's admin and the employee._
