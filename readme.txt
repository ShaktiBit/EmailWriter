for the spring boot(sb) file, (this is needed for both react and chrome extension)
	1. add two environment variables 

		GEMINI_KEY=(paste the key here)
			paste a generated API key from gemini https://aistudio.google.com/apikey
	
		GEMINI_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent

	2. keep the app running

for the react file, 
	1.open code in another window and navigate to the file in terminal using 'cd'(email-writer-react)

	2.enter the command
		npm run dev

	3.open any browser and paste 
		http://localhost:5173/

for the chrome extension(ext) file,
	1.go to chrome's extensions page and turn on developer mode

	2.click 'Load unpacked' button to navigate to email-writer-ext