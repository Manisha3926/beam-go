# beam-go
# beam-go

### Steps to run the program on our system.

1.visit https://go.dev/dl/ and install go1.18.windows-amd64.msi .

2.After successful download ,install the setup file.

3.create a folder beam-go in 44517 folder.

4.create a repository name beam-go.

5.Type this command in the directory using Git bash or poweshell(run as administrator)

  go mod init github.com/<yourgithubusername>/beam-go
 
6.Instructions to run the project
 
  go get -u github.com/apache/beam/sdks/v2/go/pkg/beam - To get the Apache Beam Go SDK.
 
  go install github.com/apache/beam/sdks/v2/go/examples/wordcount - To install the wordcount program
 
  wordcount --input <PATH_TO_INPUT_FILE> --output counts - To run the program
  
 # Bonus
 
 1.create a file hello.go
 
 2.copy and paste custom hello.go program from https://github.com/PRASANNAARLA/beam-go-repo/blob/main/hello.go
 
 3.Type this command in the directory using powershell(run as administrator)
 
   go run hello.go
  
