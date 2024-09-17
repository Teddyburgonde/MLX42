Description de toutes les fonctions de la MLX42 ! 😊 

```c
const char* mlx_strerror(mlx_errno_t val);
```

- Description : Récupère la description 
en anglais du code d'erreur.
- Paramètre : val Le code d'erreur.
- Return : La chaîne de caractères décrivant
le code d'erreur.

```c
mlx_t* mlx_init(int32_t width, int32_t height, const char* title, bool resize);
```
- Description : Initialise une nouvelle instance de MLX42.
- Paramètres :
        width La largeur de la fenêtre.
        height La hauteur de la fenêtre.
        title Le titre de la fenêtre.
        resize Activer ou non le redimensionnement de la fenêtre.
- Return : Un pointeur vers la structure MLX ou null en cas d'échec.



