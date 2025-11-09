
A voice-first, offline web app that enables any user including non-literate individuals to record
daily electricity usage by speaking or tapping large digits. The app instantly delivers spoken
reports on usage totals, detects spikes (mean + 2σ), compares weekday vs weekend patterns and
predicts upcoming electricity bills. 

How It Addresses the Problem:
This innovation eliminates literacy and technical barriers by replacing reading and typing with
speech. It empowers households and small businesses to track and manage electricity usage
effectively.

Innovation and Uniqueness:
• Fully offline and private — stores all data locally.
• Voice input/output — accessible for illiterate users.
• Built purely with HTML, CSS, and JavaScript — lightweight, install-free, and cross-platform.
2. TECHNICAL APPROACH

Technologies to be Used:
• Frontend: HTML, CSS, JavaScript (no external libraries)
• APIs: Web Speech Recognition (input), Speech Synthesis (output)
• Data Handling: Browser localStorage, File API for CSV export/import

Methodology and Process:
1. User speaks daily unit usage; speech recognition converts it to text.
2. Data is stored locally by date.
3. App analyzes data to find total usage, mean, standard deviation, spikes, and weekend trends.
