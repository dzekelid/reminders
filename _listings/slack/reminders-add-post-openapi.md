---
swagger: "2.0"
x-collection-name: Slack
x-complete: 0
info:
  title: Slack Add Reminders
  description: Creates a reminder.
  version: 1.0.3
host: slack.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reminders.info:
    get:
      summary: Get Reminder
      description: Gets information about a reminder.
      operationId: reminders_info
      x-api-path-slug: reminders-info-get
      parameters:
      - in: query
        name: reminder
        description: The ID of the reminder
      - in: query
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Reminders
  /reminders.complete:
    post:
      summary: Mark Reminders Complete
      description: Marks a reminder as complete.
      operationId: reminders_complete
      x-api-path-slug: reminders-complete-post
      parameters:
      - in: formData
        name: reminder
        description: The ID of the reminder to be marked as complete
      - in: header
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Reminders
  /reminders.list:
    get:
      summary: List Reminders
      description: Lists all reminders created by or for a given user.
      operationId: reminders_list
      x-api-path-slug: reminders-list-get
      parameters:
      - in: query
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Reminders
  /reminders.add:
    post:
      summary: Add Reminders
      description: Creates a reminder.
      operationId: reminders_add
      x-api-path-slug: reminders-add-post
      parameters:
      - in: formData
        name: text
        description: The content of the reminder
      - in: formData
        name: time
        description: 'When this reminder should happen: the Unix timestamp (up to
          five years from now), the number of seconds until the reminder (if within
          24 hours), or a natural language description (Ex'
      - in: header
        name: token
        description: Authentication token
      - in: formData
        name: user
        description: The user who will receive the reminder
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Reminders
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---