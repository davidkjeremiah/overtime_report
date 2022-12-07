# **Create a daily report that tracks details of employees who worked overtime**

**Scenario:**

As an Data Analyst/Python Developer, working in a medium-sized company, your manager wants you to ***create a report that tracks details of employees who are still clocked-in after 6pm and of employees who though are checked out, clocked out after 6pm*** to compensate their overtime.

In your company, there's a system that collects every clock-in and clock-out event of every employee in the company.

In our scenario, let's consider the ***system*** that collects or tracks every clock-in and clock-out event by every employee in company as an **Employee class**. 

And each event (either clock-in or clock-out) - detailing the `date`, the `name` of employee, the `department`, the `email` of the employee, the `phone number`, the `salary`, and the event `type` - let's consider them as instances of the `Employee` class.

**Libraries used:**

* pandas - for creating dataframe and saving report as a `.csv` file
* datetime - for working with dates
