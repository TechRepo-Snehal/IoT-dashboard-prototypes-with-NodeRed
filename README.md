# IoT-dashboard-prototypes-with-NodeRed

Quick-start resources for building IoT dashboard prototypes using Node-RED for presales conversations

Welcome! This repository helps presales engineers and solution consultants quickly spin up IoT dashboards using [Node-RED](https://nodered.org) — an open-source, low-code tool perfect for rapid prototyping.

💡 **Why This?**  
In early presales discussions, static slides often fail to convey the *real value* of IoT. A working prototype — even with simulated data — can dramatically improve customer conversations.

---

## 🎯 What You'll Achieve
You will learn how to develop quick working IoT dashboard prototypes with minimal efforts using NodeRed that allows to:

✅ Simulate IoT sensor data (e.g., temperature, humidity)  
✅ Trigger real-time alerts & alarms  
✅ Visualize everything on interactive dashboards  
✅ Optionally integrate with platforms like [Datacake](https://datacake.de)

---

## 📦 What's Included

| Resource | Description |
|---------|-------------|
| `flows/` folder | JSON flows for import into your Node-RED instance |
| `videos.md` | Links to helpful YouTube videos to get started |
| `blogs.md` | Curated technical blogs for learning Node-RED and Datacake |
| `screenshots/` | Deck with Example dashboards & flow visuals |

---

## 📥 How to Use

### 1️⃣ Prerequisites
- [Install Node-RED](https://nodered.org/docs/getting-started/local)
- Optional: Create a free [Datacake](https://datacake.de) account
- Download required nodes for dashboarding from "Manage Palette" section
- Download DataCake nodes from "Manage Palette" section

### 2️⃣ Import JSON Flows
- Launch Node-RED (`http://localhost:1880`)
- Click top-right menu → **Import**
- Paste or upload the JSON file from the `/flows` folder
- Deploy and start your prototype!

### 3️⃣ Simulate Data
- Use `inject` + `random` nodes to simulate sensor values
- Explore charts, alerts, and dashboards!

---

## 📹 Learning Resources

See [`videos.md`](videos.md) and [`blogs.md`](blogs.md) for handpicked tutorials on:
- Installing Node-RED
- Creating your first flow
- Adding dashboard nodes
- Simulating sensor data
- Sending data to Datacake

Happy IoT Prototyping!!
