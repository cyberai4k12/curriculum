+++
title = "AI & Cybersecurity for Teens"
[extra]
lead = "A curricular activity sequence integrating AI and Cybersecurity for High School"

[[extra.activity]]
title = "Activity 0: Intro to NetsBlox, RPCs and Simple Chat App"
duration = "2 periods (45 minutes)"
summary = "In this lesson, students will be introduced to NetsBlox, specifically the messaging blocks to create a ‘simple chat app’ (which will be extended in subsequent projects)."
objectives = [
    "learn about NetsBlox, and its key abstractions for  RPCs (Call block) and messaging (Send/Receive Message).",
]
vocabulary = [
  "Distributed Computing",
  "Remote Procedure Calls",
  "Message Passing"
]
activities = [
  "Create your <a href=\"https://editor.netsblox.org/\">NetsBlox account</a>",
  "Code-along the Map & Covid App (first 50 minutes of <a href=\"https://www.youtube.com/watch?v=KjMK23TjxO8\" target=\"_blank\">this video</a>)",
  "<a href=\"https://youtu.be/KjMK23TjxO8?t=2435\">Simple Chat App</a> (Starts at 40 min mark))",
]

[[extra.activity.student_resources]]
name = "Intro Project for NetsBlox RPCs"
link = "https://www.youtube.com/watch?v=KjMK23TjxO8"

[[extra.activity.teacher_resources]]
name = "Service Docs: Google Maps"
link = "https://editor.netsblox.org/docs/services/GoogleMaps/index.html"

[[extra.activity.teacher_resources]]
name = "Service Docs: Weather"
link = "https://editor.netsblox.org/docs/services/Weather/index.html"

[[extra.activity.teacher_resources]]
name = "Service Docs: Geolocation"
link = "https://editor.netsblox.org/docs/services/Geolocation/index.html"

[[extra.activity.additional_resources]]
name = "Explore netsblox.org"
link = "http://netsblox.org"

[[extra.activity]]
title = "Activity 1: Cryptography & Coding a Caesar Cipher"
duration = "1 class period (45 minutes)"
summary = "In this lesson, students will look at the historical significance of the Caesar Cipher and learn how to implement the shift-cipher using both paper/pencil and NetsBlox. "
objectives = [
  "learn about a simple shift-cipher",
  "encrypt/decrypt messages using paper and pencil",
  "implement shift cipher in NetsBlox"
]
vocabulary = [
  "Cipher",
  "Encrypt",
  "Decrypt",
  "Plaintext",
  "Ciphertext",
]
security_concepts = [
  "Encryption",
  "Obfuscation of information",
]
activities = [
  "Introduction to encryption & historical context of Caesar Cipher",
  "Paper/Pencil implementation of Caesar Cipher",
  "Netsblox implementation of Caesar Shift Cipher",
]
# TODO: add real-world hook
discussion = [
  "What data needs to be encrypted?",
  "What are the downsides of encrypting data?",
  "How many possible keys are possible with a Caesar Shift Cipher?",
]

[[extra.activity.student_resources]]
name = "Caesar Cipher Activity in NetsBlox"
link = "https://editor.netsblox.org/?extensions=[%22https%3A%2F%2Fnetsblox.github.io%2Fexercises%2Fautograders%2Fcaesar-shift.js%22]"

[[extra.activity.student_resources]]
name = "Brute Force Cracking Caesar Cipher" 
link = "https://editor.netsblox.org/?extensions=[%22https%3A%2F%2Fnetsblox.github.io%2Fexercises%2Fautograders%2Fcrack-caesar-brute-force.js%22]"

[[extra.activity.teacher_resources]]
name = "NetsBlox Cryptography Exercises"
link = "https://netsblox.github.io/exercises?q=cryptography"

[[extra.activity.teacher_resources]]
name = "Caesar Cipher (Wikipedia)"
link = "https://en.wikipedia.org/wiki/Caesar_cipher"

[[extra.activity.teacher_resources]]
name = "Practical Cryptography: Caesar Cipher"
link = "http://practicalcryptography.com/ciphers/caesar-cipher/"

[[extra.activity.additional_resources]]
name = "CryptoClub: Desert Oasis (Game)"
link = "https://www.cryptoclub.org/#vDesertOasis"

[[extra.activity.additional_resources]]
name = "TED Talk: Why Privacy Matters"
link = "https://www.ted.com/talks/alessandro_acquisti_what_will_a_future_without_secrets_look_like?language=en"


[[extra.activity.additional_resources]]
name = "Time it takes to brute force a password (aka why we need special characters)"
link = "https://www.techrepublic.com/article/how-an-8-character-password-could-be-cracked-in-less-than-an-hour/"

[[extra.activity]]
title = "Activity 4: Intro to Natural Language Processing and Sentiment Analysis"
duration = "120 minutes - Sentiment Analysis"
summary = "In this lesson, students will learn about classification, and the use of natural language programming and an openly available API (ParallelDots) to classify text."
objectives = [
    "learn about classification through AI/ML.",
    "explore classification in NetsBlox through the sentimental “writer” - a basic program that uses an API to classify content (i.e., words/music)."
]
extensions = "Classify music lyrics/NYT articles"
vocabulary = [
  "Machine learning",
  "Classification",
  "Natural Language Processing",
  "Sentiment Analysis",
  "Polarity",
  "API",
]
activities = [
  "Introduction to NLP and Sentiment Analysis",
  "Twitter Sentimental Writer (unplugged movies reviews)",
  "Music (song lyrics) Sentiment using Genius API (NetsBlox/View in Python)",
]
[[extra.activity.student_resources]]
name = "Sentimental Writer Starter Code"
link = "https://curriculum.netsblox.org/9-week/aiml/sentiment-starter.nb"

[[extra.activity.teacher_resources]]
name = "Sentiment Writer Teaching Guide"
path = "9-week/aiml/sentiment-guide.pdf"

[[extra.activity.teacher_resources]]
name = "Sentiment Writer Slides"
path = "9-week/aiml/sentiment.ppt"

[[extra.activity.teacher_resources]]
name = "Instructional Video"
path = "9-week/aiml/sentiment-guide.mp4"

[[extra.activity.additional_resources]]
name = "How NLP works"
link = "https://www.youtube.com/watch?v=CMrHM8a3hqw"

[[extra.activity]]
title = "Activity 4a: Intro to Sentiment Analysis & Cyberbullying"
duration = "120 minutes - Sentiment Analysis"
summary = "In this lesson, students will learn about natural language programming as an AI application. Then they will apply sentiment analysis to two different forms of media (tweets and song lyrics)."
objectives = [
  "learn about sentiment analysis on natural language applications (i.e., music lyrics).",
]
vocabulary = [
  "Natural Language Processing",
  "Sentiment Analysis",
  "Polarity",
  "API",
]
ai_concepts = [
  "TODO",
]
security_concepts = [
  "TODO",
]
activities = [
  "Introduction to NLP and Sentiment Analysis",
  "Twitter Sentimental Writer (unplugged movies reviews)",
  "Music (song lyrics) Sentiment using Genius API (NetsBlox/View in Python)",
]
hooks = [
  "Cyberbullying",  # HTML can be embedded here for links
]
discussion = [
  "What are examples of unsavory speech/behavior on social media?",
  "Have any of you have experienced some form of bullying online? What was it about (if they feel like sharing)",
  "How does cyberbullying connect to issues of cybersecurity?",
]
unplugged = "To Do (optional)"

[[extra.activity.student_resources]]
name = "Sentimental Writer Starter Code"
link = "https://curriculum.netsblox.org/9-week/aiml/sentiment-starter.nb"

[[extra.activity.teacher_resources]]
name = "Sentiment Writer Teaching Guide"
path = "9-week/aiml/sentiment-guide.pdf"

[[extra.activity.teacher_resources]]
name = "Sentiment Writer Slides"
path = "9-week/aiml/sentiment.ppt"

[[extra.activity.teacher_resources]]
name = "Instructional Video"
path = "9-week/aiml/sentiment-guide.mp4"

[[extra.activity.additional_resources]]
name = "How NLP works"
link = "https://www.youtube.com/watch?v=CMrHM8a3hqw"


+++
