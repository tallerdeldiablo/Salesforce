# Salesforce Lead Integration

A small project connecting Salesforce with PHP and MariaDB.

Visitors submit a web form that creates a lead in Salesforce. A Salesforce Flow creates a follow-up task, sends a confirmation email and forwards the lead data to a PHP webhook.

PHP validates the request and saves the lead in MariaDB. A password-protected dashboard displays the saved records.

## Technologies

- HTML and CSS
- PHP and PDO
- MariaDB
- Salesforce Web-to-Lead and Flow
- REST API requests with JSON
- cPanel hosting
- Postman for testing

## Features

- Automatic follow-up tasks and confirmation emails
- Webhook authentication using a shared key
- Required-field and email validation
- Duplicate prevention using the Salesforce lead ID
- Protected lead dashboard

## Live Form

[Try the demo form](https://salesforce-demo.ricoding.com/form.html)

Please use fictional contact details for testing.

## Scope

New leads are copied from Salesforce to MariaDB. Updates and deletions are not synchronized.
