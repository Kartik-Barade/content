# ============================================================
#                 KARTIK BARADE
# ============================================================

class KartikBarade:

    def __init__(self):
        self.name = "Kartik Barade"
        self.role = "AI/ML Student | Software Developer"
        self.location = "Pune, Maharashtra, India"

        self.interests = [
            "Artificial Intelligence",
            "Machine Learning",
            "Full Stack Development",
            "Data Analytics",
            "UI/UX Design"
        ]

        self.languages = [
            "Python",
            "Java",
            "JavaScript",
            "HTML",
            "CSS",
            "SQL"
        ]

        self.frontend = [
            "React",
            "HTML",
            "CSS",
            "JavaScript",
            "Figma"
        ]

        self.backend = [
            "Node.js",
            "REST APIs",
            "MySQL",
            "MongoDB"
        ]

        self.ml_stack = [
            "Pandas",
            "NumPy",
            "Scikit-Learn",
            "Matplotlib",
            "OpenCV",
            "MediaPipe"
        ]

        self.tools = [
            "Git",
            "GitHub",
            "VS Code",
            "Postman",
            "Jupyter",
            "Figma"
        ]

    def about_me(self):
        return """
        I am an AI/ML Engineering student passionate about
        building intelligent applications, modern web experiences,
        and practical software solutions.
        """

    def what_i_do(self):
        return {
            "AI/ML": [
                "Machine Learning",
                "Predictive Modeling",
                "Data Analysis",
                "Data Visualization"
            ],

            "Development": [
                "Full Stack Applications",
                "REST APIs",
                "Backend Development",
                "Database Applications"
            ],

            "Design": [
                "UI/UX Design",
                "Figma Prototyping",
                "Responsive Interfaces",
                "Modern Design Systems"
            ]
        }

    def current_focus(self):
        return [
            "Machine Learning",
            "Python Development",
            "Full Stack Development",
            "Data Structures & Algorithms",
            "Data Analysis",
            "UI/UX Design"
        ]


# ============================================================
#                     MY PROJECTS
# ============================================================

projects = {

    "Student Performance Prediction": {
        "type": "Machine Learning",
        "technologies": [
            "Python",
            "Pandas",
            "NumPy",
            "Scikit-Learn",
            "Jupyter"
        ],
        "features": [
            "Data preprocessing",
            "Exploratory Data Analysis",
            "Data visualization",
            "Model comparison",
            "Performance evaluation",
            "Predictive analytics"
        ]
    },

    "Bicycle & Plant Store UI/UX": {
        "type": "UI/UX Design",
        "tools": [
            "Figma",
            "Excalidraw",
            "Prototyping"
        ],
        "features": [
            "User-centered interface",
            "Product browsing flow",
            "Modern typography",
            "Responsive design",
            "Clean visual hierarchy"
        ]
    },

    "Personal Portfolio": {
        "type": "Web Development",
        "technologies": [
            "React",
            "CSS",
            "Framer Motion"
        ],
        "features": [
            "Modern UI",
            "Responsive design",
            "Interactive animations",
            "Project showcase"
        ],
        "live": "https://kartikbarade.vercel.app"
    },

    "Hand Gesture Volume Control": {
        "type": "Computer Vision",
        "technologies": [
            "Python",
            "OpenCV",
            "MediaPipe"
        ],
        "features": [
            "Real-time hand tracking",
            "Gesture recognition",
            "Volume control",
            "Computer vision"
        ],
        "repository":
            "https://github.com/kartikbarade/Hand-Gesture-Volume-Control"
    }
}


# ============================================================
#                    LEARNING PHILOSOPHY
# ============================================================

learning = [
    "Learn",
    "Build",
    "Experiment",
    "Analyze",
    "Improve",
    "Repeat"
]


# ============================================================
#                       CONNECT
# ============================================================

socials = {
    "Portfolio": "https://kartikbarade.vercel.app",
    "GitHub": "https://github.com/kartikbarade",
    "LinkedIn":
        "https://www.linkedin.com/in/kartik-barade-51a9102b1/"
}


# ============================================================
#                       START
# ============================================================

if __name__ == "__main__":

    kartik = KartikBarade()

    print("👋 Hi, I'm Kartik Barade")
    print("🤖 AI/ML Student")
    print("💻 Software Developer")
    print("🌐 Full Stack Developer")
    print("📊 Data & Machine Learning Enthusiast")

    print("\n🚀 Current Focus:")

    for skill in kartik.current_focus():
        print(f"   → {skill}")

    print("\n💡 Philosophy:")
    
    for step in learning:
        print(f"   {step}")
