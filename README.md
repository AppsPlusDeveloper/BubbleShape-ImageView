</br><b>BubbleShape-ImageView</b> Es un sistema que te permitira crear imagenes con la forma de una burbuja. Ideal para Apps de mensajeria.
    </br> </br>
    
<img src="./Preview/preview1.gif" width=300 title="Screen">
    
## Importación
 
Agrega el archivo "BubbleShapeImageView.java" a tú proyecto, también agrega "BubbleShape_attrs.xml" a la carpeta "resources/values".

## Inicio

Crea el Layout de tú BubbleImageView:

```xml
<your.package.BubbleShapeImageView
 android:id="@+id/imageview1"
 android:layout_width="250dp"
 android:layout_height="250dp"
 android:layout_marginTop="10dp"
 android:layout_marginRight="10dp"
 android:layout_marginBottom="10dp"
 android:src="@drawable/icon"
 android:layout_gravity="right"
 app:bubble_angle="10dp"
 app:bubble_arrowHeight="20dp"
 app:bubble_arrowLocation="right"
 app:bubble_arrowOffset="0dp"
 app:bubble_arrowTop="10dp"
 app:bubble_arrowWidth="10dp" />
```

¡Y eso es todo!

Para colocar la flecha hacia la izquierda solo cambia:

```xml
app:bubble_arrowLocation="left"
```
