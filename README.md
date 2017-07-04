# libft
Implementation of some of the Standard C Library functions including some additional ones

### TOC
* [About libft?](#about-libft)
* [Realized functions?](#realized-functions)
* [How use libft?](#how-use-libft)
* [How do I use the library?](#how-do-i-use-the-library)
* [Example usage](#example-usage)

### About libft?
My [Libft][1] including some of the standard C functions, additional ones and my own useful functions)).

### Realized functions?

Libc functions | Additional functions | Bonus Functions | Personal Functions
:----------- | :-----------: | :-----------: | -----------:
memset		| ft_memalloc	| ft_lstnew		| ft_sliv 
bzero		| ft_memdel		| ft_lstdelone	| ft_uppcase 
memcpy		| ft_strnew		| ft_lstdel		| ft_lowcase    
memccpy		| ft_strdel		| ft_lstadd		|     
memmove		| ft_strclr		| ft_lstiter	|     
memchr		| ft_striter	| ft_lstmap		| 
memcmp		| ft_striteri	|				| 
strlen		| ft_strmap		|				| 
strdup		| ft_strmapi	|				| 
strcpy		| ft_strequ		|				| 
strncpy		| ft_strnequ	|			| 
strcat		| ft_strsub		| | 
strlcat		| ft_strjoin	| | 
strchr		| ft_strtrim	| | 
strrchr		| ft_strsplit	| | 
strstr		| ft_itoa		|
strnstr		| ft_putchar	|
strcmp		| ft_putstr		|
strncmp		| ft_putendl	|
atoi		| ft_putnbr		|
isalpha		| ft_putchar_fd	|
isdigit		| ft_putstr_fd	|
isalnum		| ft_putendl_fd	|
isascii		| ft_putnbr_fd	|
isprint		|
toupper		|
tolower		|

### How use libft?

Call make:

	make

You should see a *libft.a* file and some object files (.o).

Now to clean up (removing the .o files and the .c files from the root), call `make clean`

You have to tell the file where your library resides and which library it is using:

`gcc -L. -lft example.c`

-L takes the path to your library. `.` in this case<br>
-l takes the name of your library. This is the set of characters that come after `lib` in your library name.

That's it. Now run it using `./a.out`

		
	As an example, after creating ft_memset as your first function, you go into the Makefile, remove the `#` in front of `FILES`, remove the `\` at the end of `ft_memset` and add a `#` in front of `ft_bzero`. 
	
	If it still looks complicated, **DON'T PANIC**, [just ask me][8] :)
4. Run Make so you can build the library:
		
		make	

## Example usage

List of my projects that use Libft:

* [get_next_line](https://github.com/oborys/get_next_line)
* [fillit](https://github.com/oborys/fillit)
* [ft_printf](https://github.com/oborys/ft_printf)
* [filler](https://github.com/oborys)
* [Lem_in](https://github.com/oborys)

