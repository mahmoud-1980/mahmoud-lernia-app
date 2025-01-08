
all: lernia

clean:
	rm -f go.mod go.sum lernia
lernia:
	go mod init lernia-app && go mod tidy
	go build -o lernia main.go
