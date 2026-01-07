<!doctype html>
<html lang="en" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Multimedia - ICT</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    body {
      box-sizing: border-box;
    }
    
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&display=swap');
    
    * {
      font-family: 'Poppins', sans-serif;
    }
    
    .quiz-option {
      transition: all 0.2s ease;
      cursor: pointer;
    }
    
    .quiz-option:hover {
      transform: translateX(4px);
    }
    
    .quiz-option.selected {
      border-width: 2px;
    }
    
    .quiz-option.correct {
      animation: correctPulse 0.5s ease;
    }
    
    .quiz-option.incorrect {
      animation: shake 0.5s ease;
    }
    
    @keyframes correctPulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.02); }
    }
    
    @keyframes shake {
      0%, 100% { transform: translateX(0); }
      25% { transform: translateX(-10px); }
      75% { transform: translateX(10px); }
    }
    
    .fade-in {
      animation: fadeIn 0.3s ease;
    }
    
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .input-field {
      transition: all 0.2s ease;
    }

    .input-field:focus {
      outline: none;
      transform: translateY(-2px);
    }

    .timer-warning {
      animation: pulse 1s ease-in-out infinite;
    }

    @keyframes pulse {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.7; }
    }

    .timer-critical {
      animation: flashRed 0.5s ease-in-out infinite;
    }

    @keyframes flashRed {
      0%, 100% { background-color: #ef4444; }
      50% { background-color: #dc2626; }
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full">
  <div id="app-wrapper" class="h-full w-full overflow-auto"><!-- Main Content -->
   <div id="main-content" class="min-h-full w-full"><!-- Header -->
    <header class="w-full py-8 px-6 shadow-sm">
     <div class="max-w-6xl mx-auto">
      <h1 id="site-title" class="text-4xl font-bold mb-2">ISTEPS-ICT SELF TUTORING EDUCATIONAL PLATFORM</h1>
      <p class="text-lg mb-1">Research Study by JOEL P. RODRIGUEZ, LPT, MAVEd</p>
      <p id="lesson-title" class="text-xl font-semibold">Interactive Multimedia - Quarter 3</p>
     </div>
    </header><!-- Content Section -->
    <main class="w-full py-8 px-6">
     <div class="max-w-6xl mx-auto"><!-- Introduction -->
      <section class="mb-8 p-6 rounded-lg shadow-md">
       <h2 class="text-2xl font-bold mb-4">What is Interactive Multimedia?</h2>
       <p class="text-lg mb-4 leading-relaxed">Interactive Multimedia is defined as any computer-delivered electronic system that allows users to control, combine, and manipulate different types of media. It signifies that interactive multimedia is about using multimedia to provide information or communicate effectively with users.</p>
      </section><!-- Uses of Interactive Multimedia -->
      <section class="mb-8 p-6 rounded-lg shadow-md">
       <h2 class="text-2xl font-bold mb-4">Uses of Interactive Multimedia</h2>
       <ul class="list-disc list-inside space-y-2 text-lg">
        <li>Education</li>
        <li>Training</li>
        <li>Games</li>
        <li>Simulation</li>
        <li>Information Presentation</li>
        <li>Corporate Presentation</li>
       </ul>
      </section><!-- Multimedia Definition -->
      <section class="mb-8 p-6 rounded-lg shadow-md">
       <h2 class="text-2xl font-bold mb-4">Understanding Multimedia</h2>
       <p class="text-lg leading-relaxed mb-4">Multimedia is content that uses a combination of different content forms such as text, audio, images, animations, video, and interactive content. Multimedia contrasts with media that use only rudimentary computer displays such as text-only or traditional forms of printed or hand-produced material.</p>
      </section><!-- Multimedia Contents -->
      <section class="mb-8 p-6 rounded-lg shadow-md">
       <h2 class="text-2xl font-bold mb-4">Multimedia Contents</h2>
       <div class="space-y-4">
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">1. Videos</h3>
         <p class="text-lg">Through video hosting sites, you can take a video and show it to the entire world (e.g., YouTube).</p>
        </div>
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">2. Sound, Music or Audio</h3>
         <p class="text-lg">If videos are too much for you, you can always record sounds. You can share your sound bites to the entire world (e.g., SoundCloud).</p>
        </div>
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">3. Online Games</h3>
         <p class="text-lg">Game developers now create what is called "browser-based games." You do not need to install these games to your computer as they run in most updated web browsers (e.g., AdventureQuest, Farmville, Candy Crush).</p>
        </div>
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">4. Online Tests</h3>
         <p class="text-lg">Online survey forms and tests that automatically display the results when finished (e.g., Online IQ and Personality Tests).</p>
        </div>
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">5. Courseware</h3>
         <p class="text-lg">Online courses that simulate the classroom online (e.g., E-learning Courses using a Learning Management System).</p>
        </div>
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">6. Podcasts</h3>
         <p class="text-lg">An episodic series of audio or text files streamed online (e.g., Stuff You Should Know, TED Talks, The Starters, Ear Biscuits).</p>
        </div>
        <div class="p-4 rounded-lg">
         <h3 class="text-xl font-semibold mb-2">7. Vodcasts</h3>
         <p class="text-lg">An episodic series of video streamed online (e.g., YouTube series/shows like Video Game High School, Good Mythical Morning).</p>
        </div>
       </div>
      </section><!-- Quiz Button -->
      <div class="text-center mb-12"><button id="quiz-button" class="px-8 py-4 rounded-lg font-bold text-xl shadow-lg hover:shadow-xl transition-all duration-200 transform hover:scale-105"> 📝 Take the Quiz </button>
      </div>
     </div>
    </main><!-- Footer -->
    <footer class="w-full py-6 px-6 text-center">
     <p id="footer-text" class="text-base font-semibold mb-1">Research Study by JOEL P. RODRIGUEZ LPT MAVED. @2024 LESSON: Interactive Multimedia TLE Quarter 3</p>
    </footer>
   </div><!-- Quiz Modal -->
   <div id="quiz-modal" class="fixed inset-0 flex items-center justify-center p-4 hidden" style="z-index: 1000;">
    <div class="absolute inset-0 opacity-90"></div>
    <div class="relative w-full max-w-3xl max-h-[90%] overflow-y-auto rounded-xl shadow-2xl p-8"><button id="close-quiz" class="absolute top-4 right-4 text-3xl font-bold hover:opacity-70 transition-opacity">×</button>
     <h2 id="quiz-title" class="text-3xl font-bold mb-6 text-center">Interactive Multimedia Quiz</h2><!-- Student Information Form -->
     <div id="student-info-form" class="mb-8">
      <div class="space-y-4">
       <div><label for="student-name" class="block text-lg font-semibold mb-2">Name:</label> <input type="text" id="student-name" class="input-field w-full px-4 py-3 rounded-lg border-2" placeholder="Enter your full name" required>
       </div>
       <div><label for="student-grade" class="block text-lg font-semibold mb-2">Grade:</label> <input type="text" id="student-grade" class="input-field w-full px-4 py-3 rounded-lg border-2" placeholder="Enter your grade level" required>
       </div>
       <div><label for="student-section" class="block text-lg font-semibold mb-2">Section:</label> <input type="text" id="student-section" class="input-field w-full px-4 py-3 rounded-lg border-2" placeholder="Enter your section" required>
       </div>
       <div id="info-error" class="text-red-600 font-semibold hidden">
        Please fill in all fields before starting the quiz.
       </div><button id="start-quiz-button" class="w-full py-3 rounded-lg font-semibold shadow-md hover:shadow-lg transition-all"> Start Quiz → </button>
      </div>
     </div><!-- Student Info Display (shown during quiz) -->
     <div id="student-info-display" class="mb-6 p-4 rounded-lg hidden">
      <div class="flex justify-between items-center flex-wrap gap-2">
       <div>
        <span class="font-semibold">Name:</span> <span id="display-name"></span>
       </div>
       <div>
        <span class="font-semibold">Grade:</span> <span id="display-grade"></span>
       </div>
       <div>
        <span class="font-semibold">Section:</span> <span id="display-section"></span>
       </div>
      </div>
     </div><!-- Timer Display -->
     <div id="timer-display" class="mb-6 p-4 rounded-lg text-center font-bold text-2xl hidden">
      ⏱️ Time Remaining: <span id="timer-value">3:00</span>
     </div>
     <div id="quiz-container"></div>
     <div id="quiz-navigation" class="mt-8 flex justify-between items-center hidden"><button id="prev-button" class="px-6 py-3 rounded-lg font-semibold shadow-md hover:shadow-lg transition-all disabled:opacity-50 disabled:cursor-not-allowed"> ← Previous </button>
      <div id="question-counter" class="text-lg font-semibold"></div><button id="next-button" class="px-6 py-3 rounded-lg font-semibold shadow-md hover:shadow-lg transition-all"> Next → </button> <button id="submit-button" class="px-6 py-3 rounded-lg font-semibold shadow-md hover:shadow-lg transition-all hidden"> Submit Quiz </button>
     </div>
     <div id="quiz-results" class="mt-8 p-6 rounded-lg hidden">
      <div class="mb-4 p-4 rounded-lg">
       <div class="text-center mb-2">
        <p class="font-semibold">Student Information</p>
       </div>
       <div class="space-y-1 text-center">
        <p><span class="font-semibold">Name:</span> <span id="result-name"></span></p>
        <p><span class="font-semibold">Grade:</span> <span id="result-grade"></span></p>
        <p><span class="font-semibold">Section:</span> <span id="result-section"></span></p>
       </div>
      </div>
      <h3 class="text-2xl font-bold mb-4 text-center">Quiz Results</h3>
      <div class="text-center mb-6">
       <p class="text-5xl font-bold mb-2" id="score-display"></p>
       <p class="text-xl" id="score-message"></p>
      </div>
      <div class="space-y-3"><button id="send-results-button" class="w-full py-3 rounded-lg font-semibold shadow-md hover:shadow-lg transition-all"> 📧 Send Results to Teacher </button> <button id="retry-button" class="w-full py-3 rounded-lg font-semibold shadow-md hover:shadow-lg transition-all"> 🔄 Retry Quiz </button>
      </div>
     </div>
    </div>
   </div>
  </div>
  <script>
    const defaultConfig = {
      background_color: '#e0f2fe',
      surface_color: '#ffffff',
      text_color: '#0c4a6e',
      primary_action_color: '#0ea5e9',
      secondary_action_color: '#38bdf8',
      font_family: 'Poppins',
      font_size: 16,
      site_title: 'ISTEPS-ICT SELF TUTORING EDUCATIONAL PLATFORM',
      lesson_title: 'Interactive Multimedia - Quarter 3',
      quiz_button_text: '📝 Take the Quiz',
      quiz_title: 'Interactive Multimedia Quiz',
      footer_text: 'Research Study by JOEL P. RODRIGUEZ LPT MAVED. @2024 LESSON: Interactive Multimedia TLE Quarter 3'
    };

    const quizQuestions = [
      {
        question: "What is Interactive Multimedia?",
        options: [
          "A type of printed material",
          "Any computer-delivered electronic system that allows users to control and manipulate different types of media",
          "A traditional form of communication",
          "A text-only computer display"
        ],
        correct: 1
      },
      {
        question: "Which of the following is NOT a use of Interactive Multimedia?",
        options: [
          "Education",
          "Training",
          "Manual typewriting",
          "Simulation"
        ],
        correct: 2
      },
      {
        question: "What does Multimedia combine?",
        options: [
          "Only text and images",
          "Different content forms such as text, audio, images, animations, video and interactive content",
          "Only audio and video",
          "Only printed materials"
        ],
        correct: 1
      },
      {
        question: "Which platform is commonly used for video hosting?",
        options: [
          "SoundCloud",
          "YouTube",
          "Microsoft Word",
          "Adobe Photoshop"
        ],
        correct: 1
      },
      {
        question: "What is SoundCloud primarily used for?",
        options: [
          "Video streaming",
          "Sharing sound bites and audio content",
          "Playing online games",
          "Creating presentations"
        ],
        correct: 1
      },
      {
        question: "What are browser-based games?",
        options: [
          "Games that must be installed on your computer",
          "Games that only work offline",
          "Games that run in updated web browsers without installation",
          "Games that require special hardware"
        ],
        correct: 2
      },
      {
        question: "Which of the following is an example of a browser-based game?",
        options: [
          "Microsoft Excel",
          "Candy Crush",
          "Adobe Illustrator",
          "Windows Media Player"
        ],
        correct: 1
      },
      {
        question: "What are online tests in multimedia?",
        options: [
          "Paper-based examinations",
          "Online survey forms and tests that automatically display results when finished",
          "Printed questionnaires",
          "Face-to-face interviews"
        ],
        correct: 1
      },
      {
        question: "What is Courseware?",
        options: [
          "A type of software for gaming",
          "Online courses that simulate the classroom online",
          "A video editing tool",
          "A social media platform"
        ],
        correct: 1
      },
      {
        question: "What system is commonly used for E-learning courses?",
        options: [
          "Gaming Console",
          "Learning Management System (LMS)",
          "Video Player",
          "Photo Editor"
        ],
        correct: 1
      },
      {
        question: "What is a Podcast?",
        options: [
          "An episodic series of audio or text files streamed online",
          "A type of video game",
          "A social media post",
          "A printed magazine"
        ],
        correct: 0
      },
      {
        question: "Which of the following is an example of a Podcast?",
        options: [
          "Farmville",
          "YouTube",
          "TED Talks (audio)",
          "Candy Crush"
        ],
        correct: 2
      },
      {
        question: "What is a Vodcast?",
        options: [
          "An audio-only podcast",
          "An episodic series of video streamed online",
          "A browser-based game",
          "An online test platform"
        ],
        correct: 1
      },
      {
        question: "Which is an example of a Vodcast?",
        options: [
          "SoundCloud audio files",
          "Good Mythical Morning (YouTube series)",
          "Online personality tests",
          "E-learning courseware"
        ],
        correct: 1
      },
      {
        question: "Interactive Multimedia is primarily about:",
        options: [
          "Using only text to communicate",
          "Traditional hand-produced materials",
          "Using multimedia to provide information or communicate",
          "Avoiding user interaction"
        ],
        correct: 2
      }
    ];

    let currentQuestion = 0;
    let userAnswers = new Array(quizQuestions.length).fill(null);
    let quizSubmitted = false;
    let studentInfo = {
      name: '',
      grade: '',
      section: ''
    };
    let timeRemaining = 180;
    let timerInterval = null;
    let timeUsed = 0;

    async function onConfigChange(config) {
      const baseFontSize = config.font_size || defaultConfig.font_size;
      const customFont = config.font_family || defaultConfig.font_family;
      const fontStack = `${customFont}, Arial, sans-serif`;

      const backgroundColor = config.background_color || defaultConfig.background_color;
      const surfaceColor = config.surface_color || defaultConfig.surface_color;
      const textColor = config.text_color || defaultConfig.text_color;
      const primaryColor = config.primary_action_color || defaultConfig.primary_action_color;
      const secondaryColor = config.secondary_action_color || defaultConfig.secondary_action_color;

      const appWrapper = document.getElementById('app-wrapper');
      if (appWrapper) {
        appWrapper.style.backgroundColor = backgroundColor;
        appWrapper.style.color = textColor;
      }
      
      const header = document.querySelector('header');
      if (header) {
        header.style.backgroundColor = surfaceColor;
        header.style.color = textColor;
      }
      
      const footer = document.querySelector('footer');
      if (footer) {
        footer.style.backgroundColor = surfaceColor;
        footer.style.color = textColor;
      }

      const sections = document.querySelectorAll('section');
      sections.forEach(section => {
        section.style.backgroundColor = surfaceColor;
        section.style.color = textColor;
      });

      const contentDivs = document.querySelectorAll('section > div > div');
      contentDivs.forEach(div => {
        div.style.backgroundColor = backgroundColor;
      });

      const quizButton = document.getElementById('quiz-button');
      if (quizButton) {
        quizButton.style.backgroundColor = primaryColor;
        quizButton.style.color = surfaceColor;
      }

      const modal = document.querySelector('#quiz-modal > div:last-child');
      if (modal) {
        modal.style.backgroundColor = surfaceColor;
        modal.style.color = textColor;
      }

      const modalBackdrop = document.querySelector('#quiz-modal > div:first-child');
      if (modalBackdrop) {
        modalBackdrop.style.backgroundColor = textColor;
      }

      const closeQuiz = document.getElementById('close-quiz');
      if (closeQuiz) {
        closeQuiz.style.color = textColor;
      }

      const prevButton = document.getElementById('prev-button');
      if (prevButton) {
        prevButton.style.backgroundColor = secondaryColor;
        prevButton.style.color = surfaceColor;
        prevButton.style.fontFamily = fontStack;
        prevButton.style.fontSize = `${baseFontSize}px`;
      }

      const nextButton = document.getElementById('next-button');
      if (nextButton) {
        nextButton.style.backgroundColor = primaryColor;
        nextButton.style.color = surfaceColor;
        nextButton.style.fontFamily = fontStack;
        nextButton.style.fontSize = `${baseFontSize}px`;
      }

      const submitButton = document.getElementById('submit-button');
      if (submitButton) {
        submitButton.style.backgroundColor = primaryColor;
        submitButton.style.color = surfaceColor;
        submitButton.style.fontFamily = fontStack;
        submitButton.style.fontSize = `${baseFontSize}px`;
      }

      const startQuizButton = document.getElementById('start-quiz-button');
      if (startQuizButton) {
        startQuizButton.style.backgroundColor = primaryColor;
        startQuizButton.style.color = surfaceColor;
        startQuizButton.style.fontFamily = fontStack;
        startQuizButton.style.fontSize = `${baseFontSize}px`;
      }

      const retryButton = document.getElementById('retry-button');
      if (retryButton) {
        retryButton.style.backgroundColor = primaryColor;
        retryButton.style.color = surfaceColor;
      }

      const sendResultsButton = document.getElementById('send-results-button');
      if (sendResultsButton) {
        sendResultsButton.style.backgroundColor = '#10b981';
        sendResultsButton.style.color = surfaceColor;
      }

      const quizResults = document.getElementById('quiz-results');
      if (quizResults) {
        quizResults.style.backgroundColor = backgroundColor;
      }

      const studentInfoDisplay = document.getElementById('student-info-display');
      if (studentInfoDisplay) {
        studentInfoDisplay.style.backgroundColor = backgroundColor;
      }

      const inputFields = document.querySelectorAll('.input-field');
      inputFields.forEach(input => {
        input.style.backgroundColor = surfaceColor;
        input.style.borderColor = secondaryColor;
        input.style.color = textColor;
      });

      const labels = document.querySelectorAll('#student-info-form label');
      labels.forEach(label => {
        label.style.color = textColor;
        label.style.fontFamily = fontStack;
        label.style.fontSize = `${baseFontSize * 1.125}px`;
      });

      const siteTitle = document.getElementById('site-title');
      if (siteTitle) {
        siteTitle.textContent = config.site_title || defaultConfig.site_title;
        siteTitle.style.fontFamily = fontStack;
        siteTitle.style.fontSize = `${baseFontSize * 2}px`;
      }

      const lessonTitle = document.getElementById('lesson-title');
      if (lessonTitle) {
        lessonTitle.textContent = config.lesson_title || defaultConfig.lesson_title;
        lessonTitle.style.fontFamily = fontStack;
        lessonTitle.style.fontSize = `${baseFontSize * 1.25}px`;
      }

      if (quizButton) {
        quizButton.textContent = config.quiz_button_text || defaultConfig.quiz_button_text;
        quizButton.style.fontFamily = fontStack;
        quizButton.style.fontSize = `${baseFontSize * 1.25}px`;
      }

      const quizTitle = document.getElementById('quiz-title');
      if (quizTitle) {
        quizTitle.textContent = config.quiz_title || defaultConfig.quiz_title;
        quizTitle.style.fontFamily = fontStack;
        quizTitle.style.fontSize = `${baseFontSize * 1.875}px`;
      }

      const footerText = document.getElementById('footer-text');
      if (footerText) {
        footerText.textContent = config.footer_text || defaultConfig.footer_text;
        footerText.style.fontFamily = fontStack;
        footerText.style.fontSize = `${baseFontSize}px`;
      }

      const headerSubtitle = document.querySelector('header p:not(#lesson-title)');
      if (headerSubtitle) {
        headerSubtitle.style.fontFamily = fontStack;
        headerSubtitle.style.fontSize = `${baseFontSize * 1.125}px`;
        headerSubtitle.style.color = textColor;
      }

      const allHeadings = document.querySelectorAll('h2, h3');
      allHeadings.forEach(heading => {
        heading.style.fontFamily = fontStack;
        if (heading.tagName === 'H2') {
          heading.style.fontSize = `${baseFontSize * 1.5}px`;
        } else if (heading.tagName === 'H3') {
          heading.style.fontSize = `${baseFontSize * 1.25}px`;
        }
      });

      const allParagraphs = document.querySelectorAll('p, li');
      allParagraphs.forEach(p => {
        p.style.fontFamily = fontStack;
        p.style.fontSize = `${baseFontSize}px`;
      });

      updateQuizColors();
    }

    function updateTimer() {
      const minutes = Math.floor(timeRemaining / 60);
      const seconds = timeRemaining % 60;
      const timerValue = document.getElementById('timer-value');
      const timerDisplay = document.getElementById('timer-display');
      
      if (!timerValue || !timerDisplay) return;
      
      const config = window.elementSdk ? window.elementSdk.config : defaultConfig;
      const surfaceColor = config.surface_color || defaultConfig.surface_color;
      
      timerValue.textContent = `${minutes}:${seconds.toString().padStart(2, '0')}`;
      
      if (timeRemaining <= 30) {
        timerDisplay.style.backgroundColor = '#ef4444';
        timerDisplay.style.color = surfaceColor;
        timerDisplay.classList.add('timer-critical');
        timerDisplay.classList.remove('timer-warning');
      } else if (timeRemaining <= 60) {
        timerDisplay.style.backgroundColor = '#f59e0b';
        timerDisplay.style.color = surfaceColor;
        timerDisplay.classList.add('timer-warning');
        timerDisplay.classList.remove('timer-critical');
      } else {
        timerDisplay.style.backgroundColor = '#10b981';
        timerDisplay.style.color = surfaceColor;
        timerDisplay.classList.remove('timer-warning', 'timer-critical');
      }
    }

    function startTimer() {
      if (timerInterval) {
        clearInterval(timerInterval);
      }
      
      timerInterval = setInterval(() => {
        timeRemaining--;
        timeUsed++;
        updateTimer();
        
        if (timeRemaining <= 0) {
          clearInterval(timerInterval);
          autoSubmitQuiz();
        }
      }, 1000);
    }

    function stopTimer() {
      if (timerInterval) {
        clearInterval(timerInterval);
        timerInterval = null;
      }
    }

    function addBonusTime() {
      timeRemaining += 60;
      updateTimer();
    }

    function autoSubmitQuiz() {
      if (!quizSubmitted) {
        const timerDisplay = document.getElementById('timer-display');
        if (timerDisplay) {
          timerDisplay.innerHTML = '⏰ <strong>Time\'s Up!</strong> Quiz auto-submitted.';
        }
        
        setTimeout(() => {
          submitQuiz();
        }, 1500);
      }
    }

    function updateQuizColors() {
      const config = window.elementSdk ? window.elementSdk.config : defaultConfig;
      const surfaceColor = config.surface_color || defaultConfig.surface_color;
      const textColor = config.text_color || defaultConfig.text_color;
      const primaryColor = config.primary_action_color || defaultConfig.primary_action_color;
      const secondaryColor = config.secondary_action_color || defaultConfig.secondary_action_color;

      const options = document.querySelectorAll('.quiz-option');
      options.forEach(option => {
        if (option.classList.contains('selected') && !quizSubmitted) {
          option.style.backgroundColor = primaryColor;
          option.style.borderColor = primaryColor;
          option.style.color = surfaceColor;
        } else if (option.classList.contains('correct')) {
          option.style.backgroundColor = '#10b981';
          option.style.borderColor = '#10b981';
          option.style.color = surfaceColor;
        } else if (option.classList.contains('incorrect')) {
          option.style.backgroundColor = '#ef4444';
          option.style.borderColor = '#ef4444';
          option.style.color = surfaceColor;
        } else {
          option.style.backgroundColor = surfaceColor;
          option.style.borderColor = secondaryColor;
          option.style.color = textColor;
        }
      });
    }

    function showQuestion(index) {
      const container = document.getElementById('quiz-container');
      if (!container) return;
      
      const question = quizQuestions[index];
      const config = window.elementSdk ? window.elementSdk.config : defaultConfig;
      const baseFontSize = config.font_size || defaultConfig.font_size;
      const customFont = config.font_family || defaultConfig.font_family;
      const fontStack = `${customFont}, Arial, sans-serif`;
      const surfaceColor = config.surface_color || defaultConfig.surface_color;
      const textColor = config.text_color || defaultConfig.text_color;
      const primaryColor = config.primary_action_color || defaultConfig.primary_action_color;
      const secondaryColor = config.secondary_action_color || defaultConfig.secondary_action_color;

      container.innerHTML = `
        <div class="fade-in">
          <h3 class="text-xl font-semibold mb-6" style="font-family: ${fontStack}; font-size: ${baseFontSize * 1.25}px; color: ${textColor};">
            Question ${index + 1}: ${question.question}
          </h3>
          <div class="space-y-3">
            ${question.options.map((option, i) => {
              let optionClass = 'quiz-option border-2 p-4 rounded-lg';
              let optionStyle = `font-family: ${fontStack}; font-size: ${baseFontSize}px; background-color: ${surfaceColor}; border-color: ${secondaryColor}; color: ${textColor};`;
              
              if (quizSubmitted) {
                if (i === question.correct) {
                  optionClass += ' correct';
                  optionStyle = `font-family: ${fontStack}; font-size: ${baseFontSize}px; background-color: #10b981; border-color: #10b981; color: ${surfaceColor};`;
                } else if (userAnswers[index] === i) {
                  optionClass += ' incorrect';
                  optionStyle = `font-family: ${fontStack}; font-size: ${baseFontSize}px; background-color: #ef4444; border-color: #ef4444; color: ${surfaceColor};`;
                }
              } else if (userAnswers[index] === i) {
                optionClass += ' selected';
                optionStyle = `font-family: ${fontStack}; font-size: ${baseFontSize}px; background-color: ${primaryColor}; border-color: ${primaryColor}; color: ${surfaceColor};`;
              }
              
              return `<div class="${optionClass}" data-option="${i}" style="${optionStyle}">${String.fromCharCode(65 + i)}. ${option}</div>`;
            }).join('')}
          </div>
        </div>
      `;

      if (!quizSubmitted) {
        container.querySelectorAll('.quiz-option').forEach(opt => {
          opt.addEventListener('click', function() {
            const optionIndex = parseInt(this.dataset.option);
            const wasAnswered = userAnswers[currentQuestion] !== null;
            
            userAnswers[currentQuestion] = optionIndex;
            
            if (!wasAnswered && optionIndex === question.correct) {
              addBonusTime();
              
              const timerDisplay = document.getElementById('timer-display');
              if (timerDisplay) {
                const originalContent = timerDisplay.innerHTML;
                timerDisplay.innerHTML = '🎉 <strong>+1 Minute Bonus!</strong> Correct answer!';
                timerDisplay.style.backgroundColor = '#10b981';
                
                setTimeout(() => {
                  timerDisplay.innerHTML = originalContent;
                  updateTimer();
                }, 2000);
              }
            }
            
            showQuestion(currentQuestion);
          });
        });
      }

      updateNavigation();
    }

    function updateNavigation() {
      const prevButton = document.getElementById('prev-button');
      const nextButton = document.getElementById('next-button');
      const submitButton = document.getElementById('submit-button');
      const counter = document.getElementById('question-counter');
      
      if (!prevButton || !nextButton || !submitButton || !counter) return;
      
      const config = window.elementSdk ? window.elementSdk.config : defaultConfig;
      const baseFontSize = config.font_size || defaultConfig.font_size;
      const customFont = config.font_family || defaultConfig.font_family;
      const fontStack = `${customFont}, Arial, sans-serif`;
      const textColor = config.text_color || defaultConfig.text_color;

      counter.textContent = `${currentQuestion + 1} / ${quizQuestions.length}`;
      counter.style.fontFamily = fontStack;
      counter.style.fontSize = `${baseFontSize * 1.125}px`;
      counter.style.color = textColor;

      prevButton.disabled = currentQuestion === 0;

      if (currentQuestion === quizQuestions.length - 1) {
        nextButton.classList.add('hidden');
        if (!quizSubmitted) {
          submitButton.classList.remove('hidden');
        } else {
          submitButton.classList.add('hidden');
        }
      } else {
        nextButton.classList.remove('hidden');
        submitButton.classList.add('hidden');
      }
    }

    function startQuiz() {
      const name = document.getElementById('student-name');
      const grade = document.getElementById('student-grade');
      const section = document.getElementById('student-section');
      const errorDiv = document.getElementById('info-error');

      if (!name || !grade || !section) return;

      const nameVal = name.value.trim();
      const gradeVal = grade.value.trim();
      const sectionVal = section.value.trim();

      if (!nameVal || !gradeVal || !sectionVal) {
        if (errorDiv) errorDiv.classList.remove('hidden');
        return;
      }

      if (errorDiv) errorDiv.classList.add('hidden');

      studentInfo = { name: nameVal, grade: gradeVal, section: sectionVal };

      const displayName = document.getElementById('display-name');
      const displayGrade = document.getElementById('display-grade');
      const displaySection = document.getElementById('display-section');
      
      if (displayName) displayName.textContent = nameVal;
      if (displayGrade) displayGrade.textContent = gradeVal;
      if (displaySection) displaySection.textContent = sectionVal;

      const infoForm = document.getElementById('student-info-form');
      const infoDisplay = document.getElementById('student-info-display');
      const timerDisplay = document.getElementById('timer-display');
      const navigation = document.getElementById('quiz-navigation');
      
      if (infoForm) infoForm.classList.add('hidden');
      if (infoDisplay) infoDisplay.classList.remove('hidden');
      if (timerDisplay) timerDisplay.classList.remove('hidden');
      if (navigation) navigation.classList.remove('hidden');

      timeRemaining = 180;
      timeUsed = 0;
      updateTimer();
      startTimer();

      showQuestion(currentQuestion);
    }

    function submitQuiz() {
      stopTimer();
      quizSubmitted = true;
      let score = 0;

      quizQuestions.forEach((question, index) => {
        if (userAnswers[index] === question.correct) {
          score++;
        }
      });

      const percentage = Math.round((score / quizQuestions.length) * 100);
      const config = window.elementSdk ? window.elementSdk.config : defaultConfig;
      const baseFontSize = config.font_size || defaultConfig.font_size;
      const customFont = config.font_family || defaultConfig.font_family;
      const fontStack = `${customFont}, Arial, sans-serif`;
      const textColor = config.text_color || defaultConfig.text_color;

      const resultName = document.getElementById('result-name');
      const resultGrade = document.getElementById('result-grade');
      const resultSection = document.getElementById('result-section');
      
      if (resultName) resultName.textContent = studentInfo.name;
      if (resultGrade) resultGrade.textContent = studentInfo.grade;
      if (resultSection) resultSection.textContent = studentInfo.section;

      const scoreDisplay = document.getElementById('score-display');
      const scoreMessage = document.getElementById('score-message');
      
      const timeMinutes = Math.floor(timeUsed / 60);
      const timeSeconds = timeUsed % 60;
      const timeString = `${timeMinutes}:${timeSeconds.toString().padStart(2, '0')}`;
      
      if (scoreDisplay) {
        scoreDisplay.textContent = `${score}/${quizQuestions.length} (${percentage}%)`;
        scoreDisplay.style.fontFamily = fontStack;
        scoreDisplay.style.fontSize = `${baseFontSize * 3}px`;
        scoreDisplay.style.color = textColor;
      }

      let message = '';
      if (percentage >= 90) {
        message = `Excellent! You have mastered this topic! 🎉 Time: ${timeString}`;
      } else if (percentage >= 75) {
        message = `Great job! You have a good understanding! 👏 Time: ${timeString}`;
      } else if (percentage >= 60) {
        message = `Good effort! Review the material for better results. 📚 Time: ${timeString}`;
      } else {
        message = `Keep studying! You can do better! 💪 Time: ${timeString}`;
      }

      if (scoreMessage) {
        scoreMessage.textContent = message;
        scoreMessage.style.fontFamily = fontStack;
        scoreMessage.style.fontSize = `${baseFontSize * 1.25}px`;
        scoreMessage.style.color = textColor;
      }

      const results = document.getElementById('quiz-results');
      const navigation = document.getElementById('quiz-navigation');
      const infoDisplay = document.getElementById('student-info-display');
      const timerDisplay = document.getElementById('timer-display');
      
      if (results) results.classList.remove('hidden');
      if (navigation) navigation.classList.add('hidden');
      if (infoDisplay) infoDisplay.classList.add('hidden');
      if (timerDisplay) timerDisplay.classList.add('hidden');

      currentQuestion = 0;
      showQuestion(currentQuestion);
    }

    function resetQuiz() {
      stopTimer();
      currentQuestion = 0;
      userAnswers = new Array(quizQuestions.length).fill(null);
      quizSubmitted = false;
      timeRemaining = 180;
      timeUsed = 0;

      const nameInput = document.getElementById('student-name');
      const gradeInput = document.getElementById('student-grade');
      const sectionInput = document.getElementById('student-section');
      
      if (nameInput) nameInput.value = '';
      if (gradeInput) gradeInput.value = '';
      if (sectionInput) sectionInput.value = '';

      const results = document.getElementById('quiz-results');
      const infoDisplay = document.getElementById('student-info-display');
      const navigation = document.getElementById('quiz-navigation');
      const timerDisplay = document.getElementById('timer-display');
      const infoForm = document.getElementById('student-info-form');
      const errorDiv = document.getElementById('info-error');
      
      if (results) results.classList.add('hidden');
      if (infoDisplay) infoDisplay.classList.add('hidden');
      if (navigation) navigation.classList.add('hidden');
      if (timerDisplay) timerDisplay.classList.add('hidden');
      if (infoForm) infoForm.classList.remove('hidden');
      if (errorDiv) errorDiv.classList.add('hidden');
    }

    // Event Listeners
    const quizButton = document.getElementById('quiz-button');
    if (quizButton) {
      quizButton.addEventListener('click', function() {
        const modal = document.getElementById('quiz-modal');
        if (modal) modal.classList.remove('hidden');
        resetQuiz();
      });
    }

    const closeQuiz = document.getElementById('close-quiz');
    if (closeQuiz) {
      closeQuiz.addEventListener('click', function() {
        const modal = document.getElementById('quiz-modal');
        if (modal) modal.classList.add('hidden');
        stopTimer();
      });
    }

    const startQuizButton = document.getElementById('start-quiz-button');
    if (startQuizButton) {
      startQuizButton.addEventListener('click', startQuiz);
    }

    const prevButton = document.getElementById('prev-button');
    if (prevButton) {
      prevButton.addEventListener('click', function() {
        if (currentQuestion > 0) {
          currentQuestion--;
          showQuestion(currentQuestion);
        }
      });
    }

    const nextButton = document.getElementById('next-button');
    if (nextButton) {
      nextButton.addEventListener('click', function() {
        if (currentQuestion < quizQuestions.length - 1) {
          currentQuestion++;
          showQuestion(currentQuestion);
        }
      });
    }

    const submitButton = document.getElementById('submit-button');
    if (submitButton) {
      submitButton.addEventListener('click', submitQuiz);
    }

    const retryButton = document.getElementById('retry-button');
    if (retryButton) {
      retryButton.addEventListener('click', resetQuiz);
    }

    const sendResultsButton = document.getElementById('send-results-button');
    if (sendResultsButton) {
      sendResultsButton.addEventListener('click', function() {
        let score = 0;
        quizQuestions.forEach((question, index) => {
          if (userAnswers[index] === question.correct) {
            score++;
          }
        });
        
        const percentage = Math.round((score / quizQuestions.length) * 100);
        const timeMinutes = Math.floor(timeUsed / 60);
        const timeSeconds = timeUsed % 60;
        const timeString = `${timeMinutes}:${timeSeconds.toString().padStart(2, '0')}`;
        
        const subject = encodeURIComponent('Interactive Multimedia Quiz Results - ' + studentInfo.name);
        const body = encodeURIComponent(
          'INTERACTIVE MULTIMEDIA - ICT LESSON\n' +
          'Quiz Results\n\n' +
          '===========================================\n' +
          'STUDENT INFORMATION\n' +
          '===========================================\n' +
          'Name: ' + studentInfo.name + '\n' +
          'Grade: ' + studentInfo.grade + '\n' +
          'Section: ' + studentInfo.section + '\n\n' +
          '===========================================\n' +
          'QUIZ PERFORMANCE\n' +
          '===========================================\n' +
          'Score: ' + score + '/' + quizQuestions.length + '\n' +
          'Percentage: ' + percentage + '%\n' +
          'Time Taken: ' + timeString + '\n\n' +
          '===========================================\n' +
          'DETAILED ANSWERS\n' +
          '===========================================\n' +
          quizQuestions.map((q, i) => {
            const studentAnswer = userAnswers[i] !== null ? q.options[userAnswers[i]] : 'No answer';
            const correctAnswer = q.options[q.correct];
            const isCorrect = userAnswers[i] === q.correct ? '✓ CORRECT' : '✗ INCORRECT';
            return `\nQuestion ${i + 1}: ${q.question}\n` +
                   `Student Answer: ${studentAnswer}\n` +
                   `Correct Answer: ${correctAnswer}\n` +
                   `Status: ${isCorrect}\n`;
          }).join('\n') +
          '\n===========================================\n' +
          'Submitted via Interactive Multimedia Educational Platform\n' +
          'Research Study by JOEL P. RODRIGUEZ, LPT, MAVEd'
        );
        
        window.open('mailto:joel.rodriguez@deped.gov.ph?subject=' + subject + '&body=' + body, '_blank', 'noopener,noreferrer');
      });
    }

    const quizModal = document.getElementById('quiz-modal');
    if (quizModal) {
      quizModal.addEventListener('click', function(e) {
        if (e.target === this) {
          this.classList.add('hidden');
          stopTimer();
        }
      });
    }

    const studentName = document.getElementById('student-name');
    if (studentName) {
      studentName.addEventListener('keypress', function(e) {
        if (e.key === 'Enter') {
          e.preventDefault();
          const gradeInput = document.getElementById('student-grade');
          if (gradeInput) gradeInput.focus();
        }
      });
    }

    const studentGrade = document.getElementById('student-grade');
    if (studentGrade) {
      studentGrade.addEventListener('keypress', function(e) {
        if (e.key === 'Enter') {
          e.preventDefault();
          const sectionInput = document.getElementById('student-section');
          if (sectionInput) sectionInput.focus();
        }
      });
    }

    const studentSection = document.getElementById('student-section');
    if (studentSection) {
      studentSection.addEventListener('keypress', function(e) {
        if (e.key === 'Enter') {
          e.preventDefault();
          startQuiz();
        }
      });
    }

    // Initialize SDK
    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities: (config) => ({
          recolorables: [
            {
              get: () => config.background_color || defaultConfig.background_color,
              set: (value) => {
                config.background_color = value;
                window.elementSdk.setConfig({ background_color: value });
              }
            },
            {
              get: () => config.surface_color || defaultConfig.surface_color,
              set: (value) => {
                config.surface_color = value;
                window.elementSdk.setConfig({ surface_color: value });
              }
            },
            {
              get: () => config.text_color || defaultConfig.text_color,
              set: (value) => {
                config.text_color = value;
                window.elementSdk.setConfig({ text_color: value });
              }
            },
            {
              get: () => config.primary_action_color || defaultConfig.primary_action_color,
              set: (value) => {
                config.primary_action_color = value;
                window.elementSdk.setConfig({ primary_action_color: value });
              }
            },
            {
              get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
              set: (value) => {
                config.secondary_action_color = value;
                window.elementSdk.setConfig({ secondary_action_color: value });
              }
            }
          ],
          borderables: [],
          fontEditable: {
            get: () => config.font_family || defaultConfig.font_family,
            set: (value) => {
              config.font_family = value;
              window.elementSdk.setConfig({ font_family: value });
            }
          },
          fontSizeable: {
            get: () => config.font_size || defaultConfig.font_size,
            set: (value) => {
              config.font_size = value;
              window.elementSdk.setConfig({ font_size: value });
            }
          }
        }),
        mapToEditPanelValues: (config) => new Map([
          ['site_title', config.site_title || defaultConfig.site_title],
          ['lesson_title', config.lesson_title || defaultConfig.lesson_title],
          ['quiz_button_text', config.quiz_button_text || defaultConfig.quiz_button_text],
          ['quiz_title', config.quiz_title || defaultConfig.quiz_title],
          ['footer_text', config.footer_text || defaultConfig.footer_text]
        ])
      });
    }

    // Apply initial styles
    onConfigChange(defaultConfig);
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9ba008cf77b408ed',t:'MTc2Nzc1MzAzOS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
