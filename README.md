 # 👩‍🌾 ArduPlant · GitHub Organization

  Welcome! This org hosts every layer of the ArduPlant system: the Arduino firmware, the grafana stack, and the Vue-based web UI.

  ## 📦 Core Repositories

  - [`arduplant`](https://github.com/ma-metier/arduplant)
    MKR WiFi 1010 firmware with a built-in HTTP server (`/sensors`, `/metrics`, `/actuators/pump/commands`) plus a Node.js mock so you can prototype without hardware.

  - [`grafaplant2`](https://github.com/ma-metier/grafaplant2)
    Docker Compose setup for Prometheus + Grafana, pre-provisioned dashboards, and datasource ready to scrape `http://arduplant-ip:4000/metrics`.

  - [`vueplant`](https://github.com/ma-metier/vueplant)
    Vue 3 / Vite SPA that consumes `/api/sensors`, renders live cards, and lays the groundwork for a richer dashboard experience.
