# matcha
Tinder like project - 42 School

Golang - PostgreSQL - React
[https://cdn.intra.42.fr/pdf/pdf/17248/fr.subject.pdf]

Based on [https://tutorialedge.net/projects/chat-system-in-go-and-react/part-1-initial-setup/]

$ brew install golang

$ brew install node

$ mkdir backend
$ mkdir frontend
$ cd backend
$ GO1181MODULE=on
$ go mod init github.com/jdGo42/Matcha

note : go.sum no more created automatically

$ cd ../frontend
$ npm install -g create-react-app
$ npx create-react-app .