### Scalable order post processing system
    Design a system to send sms, mail and invoice after order is placed.
    The individual components should run as independent microservice to make it scalable. If invoice is generated succesfully, order mail should have invoice attached, otherwise a footer message "We will send invoice soon" should be present.
    Also, find limits of individual components and whole system. 
        KPI
            orders/min
            sms/min
            mails/min
            invoices/min

    Feel free to use some microframework. Don't use full fledged bloated stuff that abstracts away everything in the problem statement.

    Use OOP and keep architecture clean. You can use message queue of your choice (suggestions - AWS SQS, RabbitMq). Share the code with us in a github repo. Also preferably, share it in the beginning itself so that we can monitor progress. 

    Bonus points for handling edge cases and errors.