---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Event Dismiss Reminder
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: meeventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnameeventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: groupsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendareventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendareventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: groupsidcalendareventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendargroup/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendargroupcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendargroupsidcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: meeventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnameeventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /groups/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: groupsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /groups/{id}/calendar/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: groupsidcalendareventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendargroup/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendargroupcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /me/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: mecalendargroupsidcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder:
    post:
      summary: Event Snooze Reminder
      description: 'event: snoozeReminder Postpone a reminder until a new time.'
      operationId: Event:SnoozeReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Snooze
      - Reminder
  /users/{id | userPrincipalName}/reminderView(startDateTime=startDateTime-value,endDateTime=endDateTime-value):
    get:
      summary: User Reminder View
      description: 'user: reminderView Return a list of calendar reminders within
        the specified start and end times.'
      operationId: User:ReminderView
      x-api-path-slug: usersid--userprincipalnamereminderviewstartdatetimestartdatetimevalueenddatetimeenddatetimevalue-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      - in: header
        name: Prefer
      responses:
        200:
          description: OK
      tags:
      - User
      - Reminder
      - View
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