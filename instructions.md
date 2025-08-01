# 🚨 User-Reported Issues

Below are 3 user reports for the To-Do List application.

## 📤 **Submission Instructions**

Once you have successfully identified and fixed all 3 bugs described in these user reports:

1. **Test your fixes** to ensure all functionality works correctly
2. **Copy the contents** of your fixed `app.js` file
3. **Submit your solution** by pasting your code into the web form at: https://forms.cloud.microsoft/r/3EBXfHcKLr
4. **Include a brief explanation** of what each bug was and how you fixed it

⚠️ **Important**: Make sure your code works completely before submitting. Test all features including adding tasks, checking them off, using filters, and refreshing the page.

---

## 📋 **Issue #1: "I can't see my tasks but they're definitely there!"**

**Reporter:** sarah_dev_2024  
**Priority:** High  
**Status:** Open

### Description
Hi, I'm having a really weird problem with the todo app. When I type in a new task and click "Add Task", the input field clears and the task counter at the bottom goes up (like it says "2 tasks remaining" instead of "1 tasks remaining"), but I literally cannot see the task anywhere on the screen. 

It's like the tasks are invisible! I thought maybe it was a CSS issue but I can see the "Add Task" button and everything else just fine. The counter definitely knows the tasks exist because it keeps going up every time I add one.

### Steps to Reproduce
1. Open the todo app
2. Type "Test task" in the input field
3. Click "Add Task" button
4. Notice input clears and counter increases
5. Look for the task in the list → IT'S NOT THERE! 😤

### Expected Behavior
I should be able to see the task I just added in the list below the input.

### Actual Behavior
Task counter increases but no tasks are visible anywhere.

---

## 📋 **Issue #2: "Filter buttons don't actually filter anything"**

**Reporter:** mike_productivity  
**Priority:** Medium  
**Status:** Open

### Description
The filter buttons at the top (All, Active, Completed) are really confusing. When I click on them, they light up and look like they're working, but they don't actually change what tasks I see.

I have a mix of completed and uncompleted tasks, and no matter which filter button I click, I still see ALL of my tasks. The "Active" button should only show my uncompleted tasks, and "Completed" should only show my finished ones, right?

### Steps to Reproduce
1. Add several tasks 
2. Check off some tasks as completed (leave others unchecked)
3. Click the "Active" filter button
4. Notice it highlights but still shows ALL tasks (completed AND active)
5. Click "Completed" filter 
6. Again, shows ALL tasks instead of just completed ones

### Expected Behavior
- "All" shows all tasks
- "Active" shows only uncompleted tasks  
- "Completed" shows only completed tasks

### Actual Behavior
All three buttons show exactly the same thing - every single task regardless of completion status.

---

## 📋 **Issue #3: "My tasks disappear when I refresh the page (sometimes)"**

**Reporter:** jenny_organizer  
**Priority:** High  
**Status:** Open

### Description
This is the MOST frustrating bug. I've been using this todo app for a few days and it's been working great, but now something really weird is happening.

When I refresh the page, sometimes my tasks just vanish! But here's the really weird part - the task counter at the bottom still shows the right number. Like it will say "3 tasks remaining" but the actual task list is completely empty. 

Sometimes if I refresh again it works, but sometimes it doesn't. It seems to happen more often when I have tasks saved from previous sessions. When I first started using the app (with no saved tasks), this never happened.

### Steps to Reproduce
1. Add several tasks over multiple browser sessions
2. Close and reopen the browser (or refresh page)
3. Sometimes tasks load fine, sometimes they don't
4. When they don't load, the counter still shows correct number
5. Adding NEW tasks after this happens works fine

### Expected Behavior
All my previously saved tasks should appear every time I refresh or reopen the page.

### Actual Behavior
Saved tasks randomly don't appear on page load, even though the app clearly knows they exist (counter is correct). Very inconsistent behavior.

### Additional Notes
- This NEVER happens to my friend who just started using the app
- It ONLY happens to me after I've been using it for a while
- Clearing my browser data and starting fresh "fixes" it temporarily
- Super confusing and makes me not trust the app to save my work 😞

---


