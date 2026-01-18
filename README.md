# Algorithmic-games
App for Algorithm based games like tower of hanoi, NQueens, rat in a maze, sudoku, taxi tycoon with instructions to play and algorithm used.
Development Environment and Core Technologies 
• Android Studio: The official Integrated Development Environment (IDE) 
was used for all stages of development, including coding, debugging, and 
testing. 
• Java: This was the primary programming language, used for implementing 
all game logic, handling UI interactions, and managing backend 
functionalities, providing a robust foundation for the application’s 
complex algorithmic structures. 
• Android SDK: The necessary set of development tools, APIs, and libraries 
were utilized to build and target modern Android operating systems. 
• Game Logic Implementation: Dedicated Java classes were established to 
house the efficient, runnable code for algorithms such as Recursion (Tower 
of Hanoi) and Backtracking (N-Queens, Sudoku), instrumented to trigger 
visual updates on the UI. 
UI/UX Framework 
The application's interface was designed around modern Material Design 
principles to achieve an intuitive, engaging, and consistent user experience: 
• Material Design: Implemented extensively across all screens for visual 
appeal. This includes standardized components, navigation patterns, and 
typography. 
• androidx.cardview.widget.CardView: Utilized on the main menu to 
display each of the six games as distinct, interactive cards, enhancing 
navigation and visual modularity. 
• Gradient Backgrounds: Dynamically applied across various screens 
using drawable resources to enhance visual appeal and provide thematic 
distinction between different game modules. 
• Material Components for Android: Employed for standard UI elements 
like responsive buttons, text fields, and integrated bottom navigation to 
maintain consistency and accessibility. 
Chatbot Integration 
• Chatbot Integration: The application utilizes the Groq API to power its 
integrated chatbot. This integration allows for extremely fast, low-latency 
responses. User queries are sent to the Groq LLM endpoint along with 
contextual metadata (e.g., the current game being played), allowing the 
chatbot to provide explanations of the underlying algorithm, and steps 
toward a solution without requiring the user to exit the game environment.
