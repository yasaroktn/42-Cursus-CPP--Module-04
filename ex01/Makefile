NAME = zoo

SRC = main.cpp Animal.cpp Cat.cpp Dog.cpp WrongAnimal.cpp WrongCat.cpp Brain.cpp

CC = c++
FLAGS = -Wall -Wextra -Werror -std=c++98
RM = rm -rf

all: $(NAME)

$(NAME): $(SRC)
	@$(CC) $(FLAGS) $(SRC) -o $(NAME)

clean:
	@$(RM) $(NAME)

fclean:
	@$(RM) $(NAME)

re: clean all

.PHONY: all clean re