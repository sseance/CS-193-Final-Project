# Adaptive Assignment Scheduler

## Project Goal
A java application that helps college students organize assignments by automatically scheduling tasks around their availability and their deadlines.

## MVP Features
- Add, edit, and remove assignments with deadlines and estimated durations.
- Enter available study time slots
- Generate schedules using a greedy deadline-based algorithm
- Mark assignments as completed and record actual completion times.
- Save and load data using CSV files.

## Future Plans
- Predict assignment durations using previous completion times.
- Automatically reschedule tasks when plans change.
- Add Google Calendar Integration

## Tech Stack
- Language: Java
- Libraries: java.util, java.time, java.io
- Storage: CSV files
- Interface: Command-line interface (CLI)
- Scheduling: Greedy algorithm prioritizing deadlines
- External APIs: None

## Design Documents
### Eisenhower Matrix
![Eisenhower Matrix][docs/eisenhower matrix.pdf]

### System Diagram
![System Diagram][docs/System-Diagram.png]
