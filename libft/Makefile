SOURCES = $(wildcard *.c)
		
CC	=	cc

CFLAGS	=	-g -Wall -Wextra -Werror

NAME	=	libft.a

OBJECTS	=	$(SOURCES:.c=.o)

all	:	$(NAME)

$(NAME)	:	$(OBJECTS)
			ar r $(NAME) $(OBJECTS)

clean:
		rm -rf $(OBJECTS)

fclean	:	clean
			rm -rf $(NAME)

re	:	fclean all