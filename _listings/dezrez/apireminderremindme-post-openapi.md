---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Sets a reminder
  version: 1.0.0
  description: Sets a reminder.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/todo/general/savetodo:
    post:
      summary: "Saves or Updates a General ToDo \r\nThis is currently used to save
        quick reminders"
      description: "Saves or updates a general todo \r\nthis is currently used to
        save quick reminders."
      operationId: GeneralToDo_SaveToDoBytoDoSave
      x-api-path-slug: apitodogeneralsavetodo-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: toDoSave
        description: A wrapper for the todo save data and the various data contracts
          needed
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Saves
      - S
      - General
      - ToDo
      - This
      - Is
      - Currently
      - Used
      - To
      - Save
      - Quick
      - Reminders
  /api/reminder/remindme:
    post:
      summary: Sets a reminder
      description: Sets a reminder.
      operationId: Reminder_RemindMeBydataContract
      x-api-path-slug: apireminderremindme-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Reminder
  /api/digitalsignature/signable/remind/{eventId}:
    get:
      summary: Send a reminder for an Envelope
      description: Send a reminder for an envelope.
      operationId: DigitalSignature_RemindByeventId
      x-api-path-slug: apidigitalsignaturesignableremindeventid-get
      parameters:
      - in: path
        name: eventId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Send
      - Reminderan
      - Envelope
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