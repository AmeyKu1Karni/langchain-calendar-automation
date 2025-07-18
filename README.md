# Langchain Calendar Automation

An intelligent event management agent powered by Langchain. This tool extracts structured information (title, date, time, location, and attendees) from natural language input and schedules events in a calendar system.

## 🧠 Features

- Parses natural language for event details.
- Extracts structured data: title, date, time, location, attendees.
- Handles missing information with defaults or clarifying prompts.
- Built using Langchain and Google Generative AI.

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

### `requirements.txt` includes:
- `langchain==0.3.26`
- `langchain-community==0.3.27`
- `google-generativeai==0.8.5`
- `google-ai-generativelanguage==0.6.15`
- `dateparser==1.2.2`

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/langchain-calendar-automation.git
   cd langchain-calendar-automation
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**
   Open `Langchain_event_management_agent.ipynb` in Jupyter Notebook or VS Code and follow the steps.

## 📝 Example Input

```text
Schedule a meeting tomorrow at 3 PM in Conference Room A with Alice and Bob about Q3 planning.
```

### Output (structured event data):
```json
{
  "title": "Q3 planning",
  "date": "2025-07-19",
  "time": "15:00",
  "location": "Conference Room A",
  "attendees": ["Alice", "Bob"]
}
```

## ⚙️ Future Work

- Integrate with Google Calendar API or Outlook Calendar.
- Add UI for easier interaction.
- Extend to recurring events or reminders.

## 📄 License

This project is licensed under the MIT License.