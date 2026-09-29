# AI-Driven-lab-02-

# GradeFlow

React-only student grade management system. It has no backend or database; all data is held in React memory and resets on page refresh.

## Run

```bash
npm install
npm run dev
```

Build check:

```bash
npm run build
```

## Demo accounts

- Admin: `admin@example.com` / `admin123`
- Teacher: `teacher@example.com` / `teacher123`
- Approver: `approver@example.com` / `approver123`
- Student: `student@example.com` / `student123`

## Included

- Role-based client-side login
- Admin user, course, and enrollment management
- Teacher assessments and grade entry
- Weighted final grade calculation
- Grade submission, approval, publication, and locking
- Student results and GPA
- Class reports
- Append-only in-memory audit log
