# Azure Security Roles for the Cloudy Scheduler App

https://www.cloudyscheduler.com/

Introducing Cloudy Scheduler - a powerful and fully managed CRON job SaaS service that enables you to automate your tasks effortlessly in your Azure environment. With Cloudy Scheduler, you can easily create, schedule and manage your recurring jobs using a simple and intuitive web interface, eliminating the need for any manual intervention. Our service supports timezones and retries, ensuring that your jobs are executed accurately and reliably, regardless of the location of your resources. Whether you want to automate backups, run scripts, or schedule other types of repetitive tasks, Cloudy Scheduler has got you covered. With Cloudy Scheduler, you can focus on your core business, while we take care of the scheduling and execution of your jobs.

The custom Azure Security roles required for Cloudy Scheduler to perform operations in your Azure environment are:


## VM Operator Role

This role will allow the Cloudy Scheduler to perform operations on your Azure Virtual Machines. The role will have the following permissions:

- **Read Virtual Machine Status**: This permission will enable the Cloudy Scheduler to read the status of your Azure Virtual Machines.
- **Start Virtual Machines**: This permission will allow the Cloudy Scheduler to start your Azure Virtual Machines.
- **Stop Virtual Machines**: This permission will allow the Cloudy Scheduler to stop your Azure Virtual Machines.
- **Restart Virtual Machines**: This permission will allow the Cloudy Scheduler to restart your Azure Virtual Machines.

## App Service Operator Role

This role will allow the Cloudy Scheduler to perform operations on your Azure App Services and App Service Plans. The role will have the following permissions:

- **Read App Services**: This permission will enable the Cloudy Scheduler to read the details of your Azure App Services.
- **Scale Out/In App Services and App Service Plans**: This permission will allow the Cloudy Scheduler to scale your Azure App Services and App Service Plans as required.
- **Start App Services**: This permission will allow the Cloudy Scheduler to start your Azure App Services.
- **Stop App Services**: This permission will allow the Cloudy Scheduler to stop your Azure App Services.
- **Restart App Services**: This permission will allow the Cloudy Scheduler to restart your Azure App Services.

By creating these custom Azure Security roles and assigning them to the Cloudy Scheduler app, you can ensure that Cloudy Scheduler can perform the necessary operations in your Azure environment without requiring access to any other resources or permissions. This approach follows the least privilege principle, which helps to enhance the security of your Azure environment.
