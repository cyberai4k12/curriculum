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

[[extra.activity.additional_resources]]
name = "Intro to ACT Slides (use as needed to orient students to \"Why AI+Cybersecurity\")"
link = "https://docs.google.com/presentation/d/1bVGZPKy6crJFbNV2cWNZykkhATH4gU7YLqiVDh6V9Qk/edit?usp=sharing"

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
hooks = [
  "Data Encryption & Privacy",
]
discussion = [
  "What data needs to be encrypted?",
  "What are the downsides of encrypting data?",
  "How many possible keys are possible with a Caesar Shift Cipher?",
]
unplugged = [
  "Print the <a href=\"https://derekbabb.github.io/CyberSecurity/Classic_Cryptography/Caesar_Cipher/Papercraft_Caesar_Wheel.docx\">Caesar Cipher wheel</a> on cardstock (requires brad fasteners)",
  "Print <a href=\"https://derekbabb.github.io/CyberSecurity/Classic_Cryptography/Caesar_Cipher/Caesar_Cipher_Activity.docx\">Caesar Cipher Worksheet</a>"
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

# TODO: add post activity discussion/reflection

[[extra.activity]]
title = "Activity 2: Intro to Chat App"
duration = "2 class periods (45-50 minutes each). One for chat app and one for encryption/decryption of messages."
summary = "In this lesson, students are introduced to the message passing functionality of NetsBlox to create a simple chat app. (The app is extended in subsequent projects to address additional topics in this curriculum)."
objectives = [
  "Be introduced to the message creation and message send/receive blocks in NetsBlox",
  "Create a simple message passing application in NetsBlox",
  "Encrypt/decrypt messages sent to each other",
]
vocabulary = ["Message passing"]
security_concepts = [
  "Encryption",
]
activities = [
  "Code-along a <a href=\"https://youtu.be/KjMK23TjxO8?t=2435\">Simple Chat App</a> (starts at 40 minute mark)",
  "Incorporate encryption functionality from the Caesar Cipher activity to encrypt/decrypt messages sent to each other",
]
hooks = [
  "Messaging is a big part of teen communication. What are the pros/cons?",
  "Why are messages in apps like WhatsApp encrypted?",
  "Discuss <a href=\"https://theintercept.com/2022/04/04/amazon-union-living-wage-restrooms-chat-app/\">this article</a>: What are the ethical considerations?",
]
discussion = [
  "What are some ways in which you communicate with friends? Which is most common?",
  "Would you like to keep these chats private and confidential?",
  "What are some situations in which such chat should be monitored? ",
  "What is the fundamental idea behind apps like chat or text?",
]

[[extra.activity.student_resources]]
name = "Activity Walkthrough"
link = "https://drive.google.com/file/d/1YSxQ41RiXtw5N3-LaQotC1nJ9QnD72Ds/view?usp=share_link"

[[extra.activity.teacher_resources]] # TODO: add encryption in the messages passed
name = "Adding Encryption to the Chat App"
link = ""

[[extra.activity]]
title = "Activity 3: Intro to Network Security/Micro:Bit Activity"
duration = "1 class period (45-50 minutes)"
summary = "In this lesson, students will learn about port scanning and network security."
objectives = [
    "learn about scanning for devices on a network",
    "explore port scanning"
]
vocabulary = [
  "Port Scanning - looking at every possible entry-point into a computer",
  "Firewall - Software tool used to monitor and block ports",
  "Protocol - Set of rules that defines how communication would be sent",
]
activities = [
  "Students will need a Micro:bit & Computer. There should also be 2-4 Micro:bits used as “servers” in the class.",
  "Micro:bit - Server",
  "Micro:bit - Port Scanner",
]

[[extra.activity.student_resources]]
name = "Activity Instructions"
link = "https://docs.google.com/document/d/1vF3oC3ToT0c2wODSwPkltYoSk92VHthZ2pK_LPVQtag/edit#"

[[extra.activity.teacher_resources]]
name = "Nmap (Wikipedia)"
link = "https://en.wikipedia.org/wiki/Nmap"

[[extra.activity.teacher_resources]]
name = "Micro:Bit Website"
link = "https://microbit.org"

hooks = [
  "<a href=\"https://www.travelpulse.com/news/travel-technology/research-shows-25percent-of-travelers-hacked-via-public-wi-fi-while-abroad.html\">Dangers of open wifi networks</a>",
]

[[extra.activity]]
title = "Activity 4a: Client-Server Chat App"
duration = "1 class period"
summary = "In this lesson, students are introduced to the need and role for a server to moderate and mediate communication via messages. This means we need to create a server app and have client apps communicate through the server."
objectives = [
  "Be introduced to a client-server version of the chat app",
  "Understand how a chatroom works and can be created in NetsBlox",
  "Understand the role of a server app- to 1) accept connections from client apps, 2) receive their text messages and 3) resend them to every other client. Each user who wants to participate in the Chatroom needs to run a client that 1) connects to the server, 2) sends text messages to it, 3) accepts messages from the server, and 4) displays them on its screen.",
]
vocabulary = [
  "Client",
  "Server",
  "Global address",
  "Local address",
]
security_concepts = [
  "Message passing",
  "Message moderation",
  "Message encryption",
]
activities = [
  "Code-along a client-server chat app",
  "Extend it to have the server play other roles such as message translation, trying to break messages encrypted using a Caesar Cipher",
]
discussion = [
  "To Do!", # TODO: this was a duplicate of the one above
]
extensions = [
  "Translation",
  "Color-coding messages based on sender",
  "Persistence (show the last 10 messages on first connect)",
  "Scrolling",
]
reflections = [
  "How are secure messages passed over the open web?",
  "Public Key Encryption - <a href=\"\">CS Unplugged Activity</a> & <a href=\"https://www.youtube.com/watch?v=GSIDS_lvRv4\">Computerphile</a>",
  "<a href=\"https://www.youtube.com/watch?v=NmM9HA2MQGI\">Overview of PKE & Diffie-Hellman</a>",
]

[[extra.activity.student_resources]]
name = "Chatroom Activity Walkthrough"
link = "https://drive.google.com/file/d/1BH5Kxtj2lXX5wA3E7QsXiw_jKrBvI5m5/view?usp=share_link"

[[extra.activity.teacher_resources]]
name = "Completed Chat Client"
path = "act/4/ChatClient.nb"

[[extra.activity.teacher_resources]]
name = "Completed Chat Server"
path = "act/4/ChatServer.nb"

[[extra.activity]]
title = "Activity 4b: Denial of Service Attacks (Extending Chat App)"
duration = "1 class period"
summary = "In this lesson, students extend the previous chat application to explore denial of service (DoS) attacks."
objectives = [
  "",
]
vocabulary = [
  "Denial of Service (DoS)",
  "Distributed Denial of Service (DDoS)",
  "rate limiting"
]
security_concepts = [
  "Denial of Service",
  "Distributed Denial of Service",
]
ai_concepts = [
  "Rule-based AI: An AI system that comprises a set of human-coded rules that result in pre-defined outcomes (similar to if-then logic)."
]
activities = [
  "Discuss Denial of Service attacks",
  "Discuss how DoS attack can be simulated in the client-server chat app (What will make the server unable to accomplish its role)",
  "Students simulate an actual attack on the Chat App server",
  "Discuss the ways in which the server can protect itself from such attacks",
  "Implement one or more such strategies in student groups",
  "End discussion with the idea of a rule-based AI system that can use data to develop an if-then set of rules to mitigate DoS attacks",
]
discussion = [
  "Are there any weaknesses to the mitigation techniques you used?",
  "What if the user made up new usernames?",
  "Could you verify that the user is not a bot?",
]
extensions = [
  "Add a registration step for users so they have to create an account before sending messages",
  "Add a login step where the user needs to provide a password",
  "Use a token (such as a big random number) issued on successful login to ensure the user isn't spoofing their username",
]
reflections = [
  "Using examples from real-life, what are the impact/dangers of such attacks? Do you know of any activism-motivated DDoS attacks?",
  "Captchas are also one example of how this is mitigated in industry (and related to multi-factor authentication when attempting to login).",
]

[[extra.activity.student_resources]]
name = "Starter project to code a technique for mitigating DoS attacks"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=ChatClient&editMode&noRun#"

[[extra.activity.teacher_resources]]
name = "Lesson Slides"
link = "https://docs.google.com/presentation/d/1BRu54MYeCkpATJXUqoUlVs4aTnY3olbKpJ8YnLpbVfs/edit?usp=sharing"

[[extra.activity]]
title = "Activity 5a: Sentimental Writer App"
duration = "2 periods"
summary = "In this lesson, students will learn about classification, and the use of natural language programming and an openly available API (ParallelDots) to classify text."
objectives = [
    "learn about classification through AI/ML.",
    "explore classification in NetsBlox through the sentimental “writer” - a basic program that uses an API to classify content (i.e., words/music)."
]
extensions = ["Classify music lyrics/NYT articles"]
vocabulary = [
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
name = "Slides with guided activity description"
link = "https://docs.google.com/presentation/d/1iyJLMwUTH7eBfiAlXABwhLMTcC_KvYRwKZvcba7z87A/edit?usp=sharing"

[[extra.activity.student_resources]]
name = "Sentimental Writer Starter Code"  # TODO: Get a link that isn't protected...
link = "https://curriculum.netsblox.org/9-week/aiml/sentiment-starter.nb"

[[extra.activity.teacher_resources]]
name = "Sentiment Writer Teaching Guide"
path = "9-week/aiml/sentiment-guide.pdf"

[[extra.activity.teacher_resources]]
name = "Sentiment Writer Slides"
path = "9-week/aiml/sentiment.ppt"

[[extra.activity.teacher_resources]]
name = "Instructional Video (~17 minutes)"
path = "9-week/aiml/sentiment-guide.mp4"

[[extra.activity.additional_resources]]
name = "How NLP works"
link = "https://www.youtube.com/watch?v=CMrHM8a3hqw"

[[extra.activity]]
title = "Activity 5b: Intro to Sentiment Analysis & Cyberbullying"
duration = "1 class period"
summary = "In this lesson, students will extend the Client-Server Chat app and combine it with the Sentimental Writer to prevent unsavory words and phrases from being sent to others via chat."
objectives = [
  "discuss the issue of online safety and cyberbullying, the impact of harmful language",
  "explore how we can use AI to detect and prevent sending hurtful words via chat",
]
vocabulary = [
]
ai_concepts = [
  "classification",
]
security_concepts = [
  "cyberbullying",
  "online safety",
]
activities = [
  "\"Chat App meets Sentimental Writer\" - extend the chat app to use the ParallelDots service to determine if we should flag/block text.",
]
hooks = [
  "<a href=\"https://www.kcur.org/podcast/up-to-date/2021-09-16/white-hat-hackers-stand-up-to-cyberbullies\">White Hat Hackers Stand Up to Cyberbullies</a>",
  "<a href=\"https://time.com/5916772/kid-of-the-year-2020/\">TIME's First-Ever Kid of the Year</a>"
]
discussion = [
  "What are some of the harms teens and young people face on social media & the internet?",
  "Now that we know that we can use AI to classify text as negative or hate speech, or sarcasm, how can we use it to tackle the use of harmful language in cyberspace?",
  "How is cyberbullying related to cybersecurity?",
  "How do you think apps like “Safe Search” or automated censoring of content (posts/tweets) work?",
]
reflections = [
  "What can technology companies and society do to prevent cyberbullying?",
  "<a href=\"https://tech.hindustantimes.com/mobile/news/tinder-will-now-use-ai-to-ask-if-you-really-want-to-send-that-offensive-message-71621519383314.html\">Tinder will now use AI to ask if you really want to send that offensive message</a>",
  "<a href=\"https://www.perspectiveapi.com/\">Perspective API</a>"
]

[[extra.activity.student_resources]]
name = "Starter Project"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=ModeratedChatTemplate&editMode&noRun"

[[extra.activity.teacher_resources]]
name = "Chat Server (only one needs to be run by the teacher)"
path = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=ChatServer&"

[[extra.activity.teacher_resources]]
name = "Lesson Slides"
path = "https://docs.google.com/presentation/d/19VM4LtLZUcaVXoJWwL7j_B5O4pMzHm0xta3u-diLW4g/edit?usp=sharing"


[[extra.activity]]
title = "Activity 6: Intro to Machine Learning & Classification"
duration = "1 class period"
summary = "In this lesson, students will learn about machine learning as an AI technique and what it means to train a model. They will explore AI applications using pre-trained models available online."
objectives = [
  "learn about machine learning as an AI technique",
  "learn about classification and explore what it means to “classify” something using machine learning models",
]
vocabulary = [
  "AI",
  "machine learning",
  "classification",
  "models",
  "training a model",
]
activities = [
  "Discuss how AI is all-pervasive today",
  "Watch ML video/slides (in student resources), discuss",
  "Explore one or more AI/ML tools and share",
  "Discuss rule-based AI vs ML",
]
hooks = [
  "Any big AI/ML example from everyday life including ChatGPT, Netflix, Amazon, etc",
]
discussion = [
  "How is rule-based AI different from machine learning?",
]

[[extra.activity.student_resources]]
name = "Teachable Machine"
link = "https://teachablemachine.withgoogle.com/v1/"

[[extra.activity.student_resources]]
name = "Drawing Completion Tool (SketchRNN)"
link = "https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html"

[[extra.activity.student_resources]]
name = "Recognizing emotions in pictures"
link = "https://azure.microsoft.com/en-us/services/cognitive-services/face/#demo"

[[extra.activity.teacher_resources]]
name = "Lesson Slides"
link = "https://docs.google.com/presentation/d/1k1H8KuV1AV0KYhZcFkesrlDE2oe7IbF46jrq8rc52uI/edit?usp=share_link"

[[extra.activity.additional_resources]]
name = "More machine learning exploration links & resources"
link = "https://docs.google.com/document/d/1JVP651V-dHC-OdAy8rf8zwlg1l4K8-q66EVDPE3Tk8o/edit"

[[extra.activity]]
title = "Activity 7: Data Exploration with CODAP"
duration = "1 class period"
summary = "In this lesson, students will learn about data visualization and gain hands-on experience exploring various datasets with CODAP."
objectives = [
  "learn about data distributions",
  "learn how to explore data with CODAP",
  "learn about periodic data",
]
vocabulary = [
  "Distribution",
  "Periodic",
]
activities = [
  "Complete CODAP Tutorial (parts 1 & 2)",
  "Explore the birthday dataset as a class (answer questions in link)",
  "Explore another dataset of interest (from the additional datasets link)!",
]
discussion = [
  "Discussion questions can be found in the CODAP links",
]

[[extra.activity.student_resources]]
name = "CODAP Tutorial Part 1"
link = "https://codap.concord.org/app/static/dg/en/cert/index.html#file=examples:Getting%20started%20with%20CODAP"

[[extra.activity.student_resources]]
name = "CODAP Tutorial Part 2"
link = "https://codap.concord.org/app/static/dg/en/cert/index.html?url=https://concord-consortium.github.io/codap-data/example-documents/src/documents/get_started_2.codap"

[[extra.activity.student_resources]]
name = "Birthday Dataset in CODAP"
link = "https://codap.concord.org/releases/latest/static/dg/en/cert/index.html?url=https://concord-consortium.github.io/codap-data/SampleDocs/Mathematics/Probability/Birthdays/Birthdays.codap"

[[extra.activity.student_resources]]
name = "Additional CODAP Datasets"
link = "https://concord-consortium.github.io/codap-data/"

[[extra.activity.teacher_resources]]
name = "CODAP Educator Resources"
link = "https://codap.concord.org/for-educators/"

[[extra.activity]]
title = "Activity 8: Twitter Bot Detection"
duration = "1 period"
summary = "In this lesson, students will create rules to classify (synthetic) Twitter accounts as bots or humans then learn how they can automate this process to learn a decision tree from data. "
objectives = [
  "Gain hands-on experience with rule-based AI",
  "Learn how rules can be automatically selected to construct a decision tree from data",
]
vocabulary = []
ai_concepts = [
  "Decision Tree",
  "Rule-based AI",
  "Entropy",
]
unplugged = [
  "<a href=\"https://docs.google.com/presentation/d/1umwgpKAEhXer5jNh7bYcd9w4h2C1mtmsWsPZnjyiihI/edit?usp=share_link\">Decision Tree Unplugged Activity</a>",
]
activities = [
  "Introduce bot accounts using a real-world hook",
  "Decision Tree Unplugged Activity",
  "Explore the Twitter dataset using CODAP & create rules to classify accounts",
  "Reflect on how we created our rules and how we might automate this",
  "Decision tree learning block as Parsons problem",
]
discussion = [
  "",
]

[[extra.activity.student_resources]]
name = "Starter Code for Decision Tree Activity"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=Decision%20Tree%20Templatev2&"

[[extra.activity.teacher_resources]]
name = "Solution to Decision Tree Activity"
path = "act/8/Decision%20Tree%20Solution.nb"

[[extra.activity.additional_resources]]
name = "How to spot fake social media accounts"
link = "https://www.dw.com/en/fact-check-how-do-i-spot-fake-social-media-accounts-bots-and-trolls/a-60313035"

[[extra.activity.additional_resources]]
name = "How to tell if you’re talking to a bot"
link = "https://www.technologyreview.com/2018/07/18/141414/how-to-tell-if-youre-talking-to-a-bot/"

[[extra.activity.additional_resources]]
name = "Spot the Troll (game)"
link = "https://spotthetroll.org/"

[[extra.activity]]
title = "Activity 9: Registration Bots and Gradient Descent"
duration = "2 class periods"
summary = "In this lesson, students will be introduced to optimization, a fundamental concept in machine learning. They will then use gradient descent to optimize a simple bot detection model. "
objectives = [
  "Program a bot to register for an account",
  "Train an ML model using gradient descent",
]
vocabulary = [
  "Optimization",
  "Gradients",
  "Gradient Descent",
]
activities = [
  "Introduce registration website activity in NetsBlox",
  "Program a bot to register for an account",
  "Find the Minimum Game",
  "Implement a model for bot classification (Parsons problem)"
]

[[extra.activity.student_resources]]
name = "Account Registration Activity in NetsBlox"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=CollectBehavioralData&editMode&noRun"

[[extra.activity.student_resources]]
name = "Starter Code for Registration Bot"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=CollectBotBehavioralData%20Template&editMode&noRun"

[[extra.activity.student_resources]]
name = "Find the Minimum!"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=Find%20The%20Minimum!&"

[[extra.activity.student_resources]]
name = "Starter Code for Bot Classification"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=BehaviorDataClassification%20Templatev2&editMode&noRun"

[[extra.activity.teacher_resources]]
name = "Solution to Bot Classification Activity"
path = "act/9/BehaviorDataClassification.nb"

[[extra.activity.additional_resources]]
name = "Visualizing Different Optimization Algorithms"
link = "https://emiliendupont.github.io/2018/01/24/optimization-visualization/"

[[extra.activity]]
title = "Activity 10: Adversarial Examples"
duration = "2 periods"
summary = "In this lesson, students will learn how they can use what they learned about optimization to optimize points in a way to fool a model. They will also gain hands-on experience creating adversarial examples both in NetsBlox and using another online tool. "
objectives = [
  "Apply the concepts they learned around optimization to optimize a point (to fool the model) rather than a model",
  "Implement an optimization algorithm for generating adversarial examples",
]
ai_concepts = [
  "gradient descent",
  "optimization",
  "adversarial examples",
  "classification",
]
vocabulary = [
  "Adversarial examples",
  "Optimization",
]
activities = [
  "Visualize the predictions of the model in the previous activity for many made-up points",
  "Discuss what it would mean to move a point toward a minimum or maximum wrt the model predictions",
  "Implement an optimization algorithm on a point with the objective of fooling the model",
  "Explore an online tool for generating adversarial examples (link below)"
]
discussion = [
  "",
]

[[extra.activity.student_resources]]
name = "Break Neural Networks in the Browser"
link = "https://kennysong.github.io/adversarial.js/"

[[extra.activity.teacher_resources]]
name = "Completed Adversarial Example (check out the adversarial point sprite)"
path = "act/9/BehaviorDataClassification.nb"


[[extra.activity]]
title = "Activity 11: Generative Adversarial Networks (GANs)"
duration = "2 class periods"
summary = "In this lesson, students will learn about generative adversarial training as they explore the question \"Rather than generating a single point, can we train a model to produce realistic looking points?\""
objectives = [
  "Use the optimization concepts from a earlier lessons to brainstorm how we could optimize a model to make adversarial examples",
  "Implement the training algorithm for a generative model",
]
vocabulary = [
  "Generative-Adversarial Networks",
  "Generator",
  "Discriminator",
]
activities = [
  "Introduce the Circle GAN project (show the working example)",
  "Sketch out the pseudocode for training a model to produce adversarial examples (in the slides)",
  "Implement the training algorithm for the generator",
  "Train a GAN in the browser using GAN Lab",
]
discussion = [
]

[[extra.activity.student_resources]]
name = "Circle GAN Starter Code"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=Circle%20GAN%20Template&editMode&noRun"

[[extra.activity.student_resources]]
name = "GAN Lab"
link = "https://poloclub.github.io/ganlab/"

[[extra.activity.teacher_resources]]  # TODO: make this link protected! (Needs to be updated first)
name = "Circle GAN Solution"
link = "https://editor.netsblox.org/?action=present&Username=brian&ProjectName=Circle%20GAN&"

[[extra.activity.additional_resources]]
name = "Train a GAN in Python"
link = "https://realpython.com/generative-adversarial-networks/"

# [[extra.activity]]
# title = ""
# duration = ""
# summary = ""
# objectives = [
#   "",
# ]
# vocabulary = [
#   "",
# ]
# security_concepts = [
#   "",
# ]
# activities = [
#   "",
# ]
# discussion = [
#   "",
# ]
# extensions = [
#   "",
# ]
# reflections = [
#   "",
# ]
# 
# [[extra.activity.student_resources]]
# name = ""
# link = ""
# 
# [[extra.activity.teacher_resources]]
# name = ""
# path = ""

+++
