<div align="center">

### 🚀 Hello, World! I'm Desi! 👋

</div>

```python
class Developer:
    def __init__(self, name):
        self.name = name
        self.current_study = "Web Development at SoftUni"
        self.completed_courses = ["Python coursework"]
        self.current_focus = "HTML & CSS fundamentals"
        self.up_next = "Diving deep into JavaScript"
        self.philosophy = "Continuous learning and self-improvement"

    def display_info(self):
        print(f"🎓 Studying: {self.current_study}")
        print(f"✅ Completed: {', '.join(self.completed_courses)}")
        print(f"🖥️ Current Focus: {self.current_focus}")
        print(f"🌐 Up Next: {self.up_next}")
        print(f"🌱 Philosophy: {self.philosophy}")

class SkillsLearningPath:
    def __init__(self):
        self.completed = "Python"
        self.currently_studying = "HTML & CSS"
        self.up_next = "JavaScript"
    
    def display_path(self):
        print(f"🐍 Completed: {self.completed}")
        print(f"🌍 Currently Studying: {self.currently_studying}")
        print(f"🔜 Up Next: {self.up_next}")

class Toolkit:
    def __init__(self):
        self.ides_editors = ["VS Code", "PyCharm"]
        self.frameworks = ["Django"]
        self.tools = ["Docker", "GitHub"]
        self.learning_approach = "Always eager to explore and adopt new tools and technologies"

    def display_tools(self):
        print(f"📝 IDEs & Editors: {', '.join(self.ides_editors)}")
        print(f"🕸️ Frameworks: {', '.join(self.frameworks)}")
        print(f"🧰 Tools: {', '.join(self.tools)}")
        print(f"📈 Continuous Learning: {self.learning_approach}")

class Projects:
    def __init__(self):
        self.projects = {
            "PassKeeperApp": "My first foray into web development"
        }

    def display_projects(self):
        for project, description in self.projects.items():
            print(f"📌 {project}: {description}")

desi = Developer("Desi")
desi.display_info()

skills = SkillsLearningPath()
skills.display_path()

toolkit = Toolkit()
toolkit.display_tools()

projects = Projects()
projects.display_projects()
