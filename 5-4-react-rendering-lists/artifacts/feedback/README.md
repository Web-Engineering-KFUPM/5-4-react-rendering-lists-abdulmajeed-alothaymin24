# 5-4-react-rendering-lists-main — Feedback

## Submission

- **Lab:** 5-4-react-rendering-lists-main
- **Deadline (Riyadh / UTC+03:00):** 2026-02-25T20:59:00+03:00
- **Last commit time (from git log):** 2026-02-25T08:27:20+03:00
- **Submission marks:** **20/20** (On time)


## Files Checked

- Repo root (cwd): C:\Users\Abdul\5-4-react-rendering-lists-abdulmajeed-alothaymin24\5-4-react-rendering-lists
- Detected project root: C:\Users\Abdul\5-4-react-rendering-lists-abdulmajeed-alothaymin24\5-4-react-rendering-lists
- App: ✅ C:\Users\Abdul\5-4-react-rendering-lists-abdulmajeed-alothaymin24\5-4-react-rendering-lists\src\App.jsx
- CourseCard: ✅ C:\Users\Abdul\5-4-react-rendering-lists-abdulmajeed-alothaymin24\5-4-react-rendering-lists\src\components\CourseCard.jsx
- TaskItem: ✅ C:\Users\Abdul\5-4-react-rendering-lists-abdulmajeed-alothaymin24\5-4-react-rendering-lists\src\components\TaskItem.jsx
- DueBadge: ✅ C:\Users\Abdul\5-4-react-rendering-lists-abdulmajeed-alothaymin24\5-4-react-rendering-lists\src\components\DueBadge.jsx

---

## TODO-by-TODO Feedback

### Task 1: Render Courses (App.jsx map + CourseCard props) — **20/20**

**Checklist**
- ✅ Uses courses.map(...) to render courses
- ✅ Renders <CourseCard ... /> in the map
- ✅ Passes key prop (key={course.id} or similar)
- ✅ Passes course prop (course={course} or similar)
- ✅ Passes index prop (index={idx} or similar)
- ✅ Passes onMutateCourse prop (onMutateCourse={...})

**Deductions / Notes**
- ✅ No deductions. Good job!

### Task 2: Render Tasks (CourseCard.jsx map + TaskItem props) — **20/20**

**Checklist**
- ✅ Uses course.tasks.map(...)
- ✅ Renders <TaskItem ... /> inside the map
- ✅ Passes key={task.id} (or similar)
- ✅ Passes task prop (task={task})
- ✅ Passes onToggle + onDelete props

**Deductions / Notes**
- ✅ No deductions. Good job!

### Task 3: Conditional Rendering (&& + DueBadge label logic) — **20/20**

**Checklist**
- ✅ CourseCard shows "All caught up" using logical && (top-level check)
- ✅ CourseCard shows "No tasks" message when no tasks (&& + length check or similar)
- ✅ TaskItem shows <DueBadge /> only when task is NOT done (&&)
- ✅ DueBadge implements label logic (uses daysUntil + "Overdue"/"Due today"/"Due in")
- ✅ DueBadge returns the computed label (not placeholder text)

**Deductions / Notes**
- ✅ No deductions. Good job!

### Task 4: Interactivity (Toggle + Delete ONLY) — **20/20**

**Checklist**
- ✅ CourseCard toggleTask implemented using onMutateCourse + .map() + toggles isDone
- ✅ CourseCard deleteTask implemented using onMutateCourse + .filter() by id
- ✅ TaskItem checkbox is controlled (checked={task.isDone}) and calls onToggle(task.id) onChange
- ✅ TaskItem delete button calls onDelete(task.id) onClick

**Deductions / Notes**
- ✅ No deductions. Good job!

---

## How marks were deducted (rules)

- JS/JSX comments are ignored (so starter TODO comments do NOT count).
- Checks are intentionally light: they look for key constructs and basic structure.
- Code can be in ANY order; repeated code is allowed.
- Common equivalents are accepted, and naming is flexible.
- Missing required items reduce marks proportionally within that TODO.
