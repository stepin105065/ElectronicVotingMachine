SRC = unity/unity.c\
src/VotingSystem.c\
test/test_votingSystem.c\
main.c

INC = -Iunity\
-Iinc\
-Itest

PROJECT_NAME = MyprojectVs.exe

BUILD = build

$(PROJECT_NAME): $(SRC)
	gcc $(SRC) $(INC) -o $(PROJECT_NAME)

run:$(PROJECT_NAME)
	./${PROJECT_NAME}


clean:
	rm -rf $(PROJECT_NAME)




