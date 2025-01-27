![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Tableau

### Learning Outcomes

Upon completion of this lab, you will be able to:

- Load and integrate datasets into Tableau for analysis.
- Differentiate between and appropriately assign measurements and dimensions within Tableau.
- Construct insightful barplots to compare categorical data.
- Design a treeplot to visualize hierarchical data.
- Synthesize cross tables to examine relationships between two categorical variables.
- Assemble a comprehensive dashboard that encapsulates multiple facets of the dataset.
- Save your Tableau workbook for future reference and sharing.

### Instructions

1. **Data Import**: Begin by loading the dataset `we_fn_use_c_marketing_customer_value_analysis.csv` available [here](https://raw.githubusercontent.com/data-bootcamp-v4/data/main/we_fn_use_c_marketing_customer_value_analysis.csv) into Tableau.

2. **Gender Barplot**: Create a barplot to visualize the distribution of customers by **Gender**.

3. **Employment and Gender Barplot**: Construct a barplot that represents the number of customers by **EmploymentStatus** segmented by **Gender**.

4. **Measurements vs. Dimensions**: Review the **Measurements** and **Dimensions** identified by Tableau. Adjust them if necessary to ensure they match your data structure and analysis needs.

5. **Gender Barplot Sheet**: Develop a sheet dedicated to displaying the barplot of customer counts by **Gender**.

6. **Employment and Gender Barplot Sheet**: Prepare a separate sheet to showcase the barplot of customer counts by **EmploymentStatus** and **Gender**.

7. **State Treeplot Sheet**: Create a sheet with a treeplot (also known as a treemap) illustrating the number of customers in each **State**.

8. **Marital Status and Gender Cross Table**: Generate a cross table that breaks down the customers by Marital status and Gender.

9. **Dashboard Assembly**: Compile all the created sheets into a single, interactive dashboard for an integrated view of the data insights.

10. **Save Your Work**: Preserve your Tableau workbook by saving it as `tableau-lab.tbwx`.

Para completar este laboratorio en Tableau, sigue estos pasos:

Paso 1: Importar Datos
Abrir Tableau: Inicia Tableau en tu computadora.
Cargar el Conjunto de Datos:
Haz clic en Conectar y selecciona Archivo de texto.
Navega hasta el archivo we_fn_use_c_marketing_customer_value_analysis.csv y cárgalo.
Paso 2: Crear un Barplot de Género
Crear una Nueva Hoja:
Haz clic en el icono de Hoja en la parte inferior.
Agregar Datos al Gráfico:
Arrastra Gender desde el panel de Dimensiones al estante de Columnas.
Arrastra Number of Records desde el panel de Medidas al estante de Filas.
Configurar el Gráfico:
Tableau automáticamente creará un gráfico de barras.
Ajusta el gráfico según sea necesario (colores, etiquetas, etc.).
Paso 3: Crear un Barplot de Estado de Empleo y Género
Crear una Nueva Hoja:
Haz clic en el icono de Hoja en la parte inferior.
Agregar Datos al Gráfico:
Arrastra EmploymentStatus desde el panel de Dimensiones al estante de Columnas.
Arrastra Number of Records desde el panel de Medidas al estante de Filas.
Arrastra Gender desde el panel de Dimensiones al estante de Color en la tarjeta de Marcas.
Configurar el Gráfico:
Tableau automáticamente creará un gráfico de barras segmentado por género.
Ajusta el gráfico según sea necesario (colores, etiquetas, etc.).
Paso 4: Revisar Medidas y Dimensiones
Revisar Panel de Datos:
En el panel de datos a la izquierda, revisa las Dimensiones y Medidas.
Asegúrate de que los campos estén correctamente clasificados como Dimensiones (variables categóricas) y Medidas (variables numéricas).
Paso 5: Guardar el Trabajo
Guardar el Libro de Trabajo:
Haz clic en Archivo y selecciona Guardar como.
Guarda tu libro de trabajo para futuras referencias y para compartirlo.
Estos pasos te guiarán a través de la creación de los gráficos solicitados y la revisión de las medidas y dimensiones en Tableau.

https://github.com/data-bootcamp-v4/lab-tableau/pull/136