# Golf Expense Tracker

A simple, single-file web app for splitting expenses during multi-day group trips (golf weekends, vacations, etc.). Track who paid for what, who was present for each activity, and automatically calculate final settlements.

## Features

- **Setup**: Define trip name, participants, and activities
- **Attendance**: Mark who was present for each activity (different people may join/leave at different times)
- **Expenses**: Log who paid and for what; automatically splits costs based on attendance
- **Settlement**: See who owes whom and the final balance for each participant
- **Trip History**: Save trips and reload them later to continue adding expenses

## How to Use

1. **Open the app**: Simply download `index.html` and open it in your browser
2. **No server needed**: Everything runs locally in your browser; data is saved to your device's localStorage
3. **Share with friends**: Send them the `index.html` file — they each get their own separate history (no shared data)

### Workflow

1. **Setup tab**: Enter trip name and define activities (e.g., "Thursday Green Fees", "Friday Dinner", "Uber")
2. **Participants tab**: Add the names of everyone on the trip
3. **Attendance tab**: Check the box for each activity to mark who was present
4. **Expenses tab**: For each expense, select the activity and enter who paid and how much
5. **Settlement tab**: View the final breakdown and who owes what
6. **Save**: Click "Save Trip to History" to store the trip. Load it later to continue adding expenses

## Technical Details

- **Single HTML file**: No build process, dependencies, or server required
- **Offline-first**: All data stored in browser's localStorage
- **Private**: Data never leaves your device — each person has their own separate history
- **Browser compatibility**: Works in all modern browsers (Chrome, Safari, Firefox, Edge)

## Example

A 4-day golf weekend with 9 people:
- Thursday: 4 people (green fees + dinner)
- Friday: 6 people (green fees + dinner)
- Saturday: 8 people (green fees + dinner)
- Sunday: 5 people (brunch + drive home)

Different people pay for different things. The app splits costs fairly based on who was actually present for each activity.

## License

Free to use and modify for personal use.
