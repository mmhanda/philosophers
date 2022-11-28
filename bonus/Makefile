# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mhanda <mhanda@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/06/12 00:39:39 by mhanda            #+#    #+#              #
#    Updated: 2022/06/12 03:44:47 by mhanda           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CFILES  = philo_bonus.c util_b_0.c kill_part.c
BCFILES = $(CFILES:.c=.o)

CFLAGS = -Wall -Wextra -Werror

RM = rm -rf
NAME = philo_bonus
INC = philo_bonus.h

bonus : $(NAME)

$(NAME) : $(INC) $(BCFILES)
	$(CC) $(CFLAGS) $(BCFILES) -o philo_bonus

clean :
	$(RM) $(BCFILES)

fclean : clean
	$(RM) $(NAME)

reb : fclean bonus
