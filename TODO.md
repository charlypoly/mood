## TODOS

- Electron desktop app
  - Events fetching + auth
    - [ ] oauth process
      - https://developers.google.com/google-apps/calendar/quickstart/nodejs#prerequisites
    - [ ] store `user_id`
    - [ ] fetch event
  - Events sorting
    - tinder like UI
    - send data to AWS endpoint
  - Mood summary/analysis
    - fetch data from api for given date range
    - UI for display
    - suggestions ?

- AWS API
  - POST /mood/event
    - params = `event_id, summary, user_id, start, end`
  - GET /mood/summary?start=...&end=...
  
