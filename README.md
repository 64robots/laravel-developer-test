# 64 Robots Laravel Developer Test

## Goal

Please spend no more than 5 hours on this task.  If you cannot complete the entire task in less than 5 hours, please commit what you are able to finish within that time frame.

## Delivery

Please push your code to a public repository on Github and either PM it to Rob on Slack or email to rob@64robots.com

## Task Description

Please create a new Laravel 8 application that fulfills the following functionality.

**Please note: There is no frontend component to this. These are API routes only. Please create tests for all endpoints to show they are functioning as required by the test.**

1. A user can add people
2. A user can connect people together as families
3. A user can see a family tree to any particular Person in the application 
4. Each time a new person is added, a new Notification should be dispatched to this Slack webhook: https://hooks.slack.com/services/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 - use Laravel Notifications and this Slack notification package: https://github.com/laravel/slack-notification-channel

## Task Requirements

1. Please use Laravel 8
2. Please test as you would in your own applications. PHPUnit or Pest are fine.

## Task Details

For the sake of the test, you will be evaluated solely on two items:

1. Your PHP code
2. Your tests

The most important part is that we should be able to quickly look at and understand how you write code and how it jives with our coding standards. 
