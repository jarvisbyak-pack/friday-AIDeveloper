# Friday Web UI V2

Motion-first Friday interface inspired by modern AI-orb assistants.

Features: animated AI core, idle/listening/thinking/speaking states, browser speech input/output, responsive layout, n8n webhook configuration, and GitHub Pages compatibility.

API: POST JSON `{"message":"Hello Friday"}` and return JSON such as `{"output":"Hello. How can I help?"}`.

The n8n endpoint must allow browser CORS requests. No API secrets belong in this frontend.
