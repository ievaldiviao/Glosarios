# GLOSARIO DE LINUX

1. Concatena archivos y muestra archivos:
	cat *fich1 [..fichN]*
	**ejemplo:** cat /etc/passwd
		     cat dict1 dict2 dict

2. Cambia de directorio:
	cd *[dir]*
	**ejemplo:** cd /tmp

3. Cambia los permisos de un archivo:
	chmod *permisos fich*
	**ejemplo:** chmod +x miscript

4. Cambia el dueño un archivo:
	chown *usuario:grupo fich*
	**ejemplo:** chown nobody miscript

5. Copia archivos:
	cp *fich1...fichN dir*
	**ejemplo:** cp foo foo.backup

6. Encuentra diferencia entre archivos:
	diff *[-e]arch1 arch2*
	**ejemplo:** diff foo.c newfoo.c

7. Reporta el tamaño del directorio:
	du *[-sabr]fich*
	**ejemplo:** du -s /home/

8. Muestra el tipo de un archivo:
	file *arch*
	**ejemplo:** file arc_desconocido

9. Encuentra archivos:
	find *dir test acción*
	**ejemplo:** find . -name ''.bak" -print

10. Busca patrones en archivos:
	grep *[-cilnv] expr archivos*
	**ejemplo:** grep mike /etc/passwd

11. Muestra el inicio de un archivo:
	head *-count fich*
	**ejemplo:** head prog1.c

12. Crea un directorio:
	mkdir *dir*
	**ejemplo:** mkdir temp

13. Mueve un archivo(s) de directorio:
	mv *fich1 ..fichN dir*
	**ejemplo:** mv a.out prog1

14. Renombra un archivo:
	mv *fich1 fich2*
	**ejemplo:** mv .c prog_dir

15. Visualiza página a página un archivo(less acepta comandos vi):
	less/more *fich(s)*
	**ejemplo:** more muy_largo.c
		     less muy_largo.c

16. Crea un acceso directo a un archivo:
	ln *[-s] fich acceso*
	**ejemplo:** ln -s /users/mike/.profile

17. Lista el contenido del directorio:
	ls
	**ejemplo:** ls -l /usr/bin

18. Muestra la ruta del directorio actual:
	pwd
	**ejemplo:** Pwd

19. Borra un fichero:
	rm *fich*
	**ejemplo:** rm foo.c

20. Borra un nodo de directorio:
	rm *-r dir*
	**ejemplo:** -rf prog_dir

21. Borra un directorio vacío:
	rmdir *dir*
	**ejemplo:** rmdir prog_dir

22. Muestra el final de un archivo:
	tail *-count fich*
	**ejemplo:** tail prog1.c

23. Edita un archivo:
	vi *fich*
	**ejemplo:** vi .profile
