# **************************************************************************** #
#                                                                              #
#                                                         ::::::::             #
#    Makefile                                           :+:    :+:             #
#                                                      +:+                     #
#    By: akramp <marvin@codam.nl>                     +#+                      #
#                                                    +#+                       #
#    Created: 2020/07/27 10:10:32 by akramp        #+#    #+#                  #
#    Updated: 2020/10/24 18:27:56 by akramp        ########   odam.nl          #
#                                                                              #
# **************************************************************************** #

NAME = ex02
CC = clang++
FLAGS = -Wall -Werror -Wextra

#✧･ﾟ: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ *✧･ﾟ:* SOURCES ✧*:･ﾟ✧: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ﾟ: *✧･ﾟ:#

SRC = Array.cpp

INCLUDES = Array.hpp

#✧･ﾟ: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ *✧･ﾟ:* COLORS ✧*:･ﾟ✧: *✧･ﾟ:* ✧ *:･ﾟ✧*:･ﾟ✧✧･ﾟ: *✧･ﾟ:#

ORANGE	= 	\033[38;5;208m
YELLOW2	= \033[38;5;221m
WHITE	= \033[38;5;230m
BLUE		= \033[38;5;75m

#✧･ﾟ: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ *✧･ﾟ:*  RULES  ✧*:･ﾟ✧: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ﾟ: *✧･ﾟ:#

all: $(NAME)

$(NAME): $(SRC) $(INCLUDES)
	@$(CC) $(FLAGS) $(SRC) -o $(NAME)
	@echo "$(ORANGE)\n✧･ﾟ: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ *✧･ﾟ:*✧✧*:･ﾟ✧✧･"
	@echo "$(BLUE)✨\t    ᴄᴏᴍᴘɪʟᴀᴛɪᴏɴ ᴅᴏɴᴇ!\t\t✨"
	@echo "$(ORANGE)✧･ﾟ: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ *✧･ﾟ:*✧✧*:･ﾟ✧✧･"

stars:
	@echo "$(BLUE)\n✧･ﾟ: *✧･ﾟ:*  *:･ﾟ✧*:･ﾟ✧✧･ *✧･ﾟ:*✧✧*:･ﾟ✧✧･\n"

clean:
	@echo "$(ORANGE)🌻\t    🄲 🄻 🄴 🄰 🄽 🄸 🄽 🄶 ...\t\t💫$(WHITE)\n"
	rm -f ./*~ ./*# a.out $(OBJ)
	@echo "\n$(YELLOW2)✨\t    Cleaning Done!$(WHITE)\t\t⚡"

fclean: clean stars
	@echo "$(ORANGE)🌻\t    ℝ𝕖𝕞𝕠𝕧𝕚𝕟𝕘 $(NAME)...\t💫\n$(WHITE)"
	rm -f $(NAME)
	@echo "\n$(YELLOW2)✨\t    Removed $(NAME)!$(WHITE)\t\t⚡"

re: fclean all
