swagger: "2.0"
x-collection-name: Slack
x-complete: 1
info:
  title: Slack
  description: one-way-to-interact-with-the-slack-platform-is-its-http-rpcbased-web-api-a-collection-of-methods-requiring-oauth-2-0based-user-bot-or-workspace-tokens-blessed-with-related-oauth-scopes-
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
  /reminders.delete:
    post:
      summary: Delete Reminders
      description: Deletes a reminder.
      operationId: reminders_delete
      x-api-path-slug: reminders-delete-post
      parameters:
      - in: formData
        name: reminder
        description: The ID of the reminder
      - in: header
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messaging
      - Reminders