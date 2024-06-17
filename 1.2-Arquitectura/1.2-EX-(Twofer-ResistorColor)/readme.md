#Ejercicios de exercism



3. Color Resistor

export const colorCode = (color: string) => {
return COLORS.indexOf(color.toLowerCase());
};

export const COLORS = [
"black",
"brown",
"red",
"orange",
"yellow",
"green",
"blue",
"violet",
"grey",
"white",
];

La función colorCode toma un parámetro color de tipo string y utiliza el método indexOf para buscar el índice de ese color en la matriz COLORS. La función indexOf devuelve el primer índice en el que se encuentra un elemento dado en la matriz, o -1 si no se encuentra. En este caso, se convierte el color proporcionado a minúsculas antes de buscarlo en la matriz para asegurar que la búsqueda sea insensible a mayúsculas y minúsculas.

La matriz COLORS contiene una lista de colores predefinidos. Cada color está representado como una cadena de texto.

Al exportar tanto la función colorCode como la matriz COLORS, se hace posible utilizarlas en otros archivos TypeScript mediante la importación.
