
all: lernia

clean:
	rm -f go.mod go.sum lernia
lernia:
	go mod init mahmoud-lernia-app && go mod tidy
	go build -o mahmoud-lernia main.go
