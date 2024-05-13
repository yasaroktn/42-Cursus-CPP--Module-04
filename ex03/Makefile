NAME = zoo

SRC = main.cpp AMateria.cpp Character.cpp Cure.cpp Ice.cpp MateriaSource.cpp

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