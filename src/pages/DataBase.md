---
title: Colaboradores Jusue y Enrique
---

# Uso de la Base de Datos

En esta documentación se dara el conocimiento sobre la implementación de Base de Datos en el Proyecto de Ingles.

## MongoDB

MongoDB es un sistema de gestión de bases de datos (DBMS) no relacional de código abierto que utiliza documentos flexibles en lugar de tablas y filas para procesar y almacenar diversas formas de datos.

![logo MongoBD](data:image/png;base64,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)

Como solución de base de datos NoSQL, MongoDB no requiere un sistema de gestión de bases de datos relacionales (RDBMS), por lo que proporciona un modelo de almacenamiento de datos flexible que permite a los usuarios almacenar y consultar tipos de datos multivariados con facilidad. Esto no únicamente simplifica la gestión de bases de datos para los desarrolladores, sino que también crea un entorno altamente escalable para aplicaciones y servicios multiplataforma.

## Utilización de MongoDB

MongoDB es una base de datos NoSQL ampliamente utilizada en aplicaciones modernas debido a su flexibilidad, rendimiento y facilidad de integración. En este caso, se seleccionó MongoDB como la base de datos para este proyecto por las siguientes razones:

- Modelo de datos flexible
- Escalabilidad
- Capacidades de almacenamiento de datos jerárquicos
- Despliegue rápido y administración sencilla
- Integración con tecnologías modernas


## Uso en Codigo

La base de datos fue utilizada para llevar un "registro" de  las activdades hechas y tener un mayor control e organización en la elaboracion de proyecto, esta se integrto en el apartado de los juegos en cual podemos lograr un almacenamiento de datos.

Como en los siguientes juegos:

1. __Conecxión__

    `app.use(cors())` nos permite hacer la solicitud de datos mientras que
   `app.use(json())` los datos los convierte a json

   `then` esta en caso de que la coxión sea exitosa 

   `catch` si se intercepta un error y lo escribe en la consola

    ```js
        import express, { json } from 'express';
        import cors from 'cors';
        import mongoose from 'mongoose';
        import dotenv from 'dotenv';
        import { Game } from './models/Game.js';
        dotenv.config();
        
        const app = express();
        app.use(cors());
        app.use(json());

        const connectionString = process.env.MONGO_BD_URI || "mongodb+srv://database: EkZ9946Yppn0oq1s@cluster0.nvrhj.mongodb.net/?retryWrites=true&w=majority&appName-Cluster0" // la url que se necesita para hacer la conexón con la db


        mongoose.connect(connectionString) // conexixon a mongoDB
         .then(() => {
            console.log('Connected to MongoDB');
        })
        .catch(err => {
            console.error('Error connecting to MongoDB:', err);
        });
    ```

2. __Modelo del juego__

    ```js
        import { model, Schema } from 'mongoose';
        const gameSchema = new Schema({
            title: String,
            content: String,
            words: Array
        }); //se crea el modelo del juego
        
        gameSchema.set('toJSON', {
        // se modifica el esquem para eliminar __v y el _id convertirlo a id
            transform: (document, returnedObject) → {
                returnedObject.id = returnedObject._id;
                delete returnedObject._id;
                delete returnedObject.__v;
            }
        });
        
        export const Game = model('Game', gameSchema);
    ```

4. __Obtención de Datos__

    ```js
        app.get('/api/memoryContent', async (request, response) {try {
                const games = await Game.find({});
                response.json(games);
            } 
            catch (error) {
            console.error('Error al obtener los datos:', error);
            response.status(500).send('Error al obtener los datos');
            }
    ```

5. __Post__

    Este fragmento del código se encarga de manejar la creación de un nuevo juego de memoria en el servidor. El endpoint configurado es `POST /create-memory-game.`

    ```js

    app.post('/create-memory-game', async (req, res) => {
        const { title, content, words} = req.body;
        try {
            const game = new Game({
                title: title,
                content: content,
                words: words,
            });
            
            //usa el modelo y le pasa los datos del esquema con los datos de la request body
            await game.save(); // segurada
            //status code 201 Created si es que se creo bien
            res.status(201).json({ message: 'Game created successfully!', game });} 
            
            catch (e) {
                console.error(e);
                res.status(500).json({ message: 'An error occurred' error: e.message });
            }
        })
    ```

6. __Servidor en el puerto 3001__

    ```js

    const PORT = 3001;
    app.listen(PORT, () ==> {
        console.log(`Server running on port ${PORT}`)
    });

    //se abre el servidor en el puerto 3001

    ```

7. __FRONTEND__

    ```js

    const [memoryContent, setMemoryContent] = useState(() => {
        const saved MemoryContent = localStorage.getItem("memoryContent");
        
        return saved MemoryContent? JSON.parse(saved MemoryContent) : [];
        });
        //revisa si en el localStorage hay un item llmado memoryContent si no con la ternaria el memoryContent se iniciara con un array
        
        useEffect() => {
            const fetchData = () {
                axios
                .get("http://127.0.0.1:3001/api/memoryContent") // fecht de la data con un method get
                .then((response) => { 
                    // Verificar si los datos han cambiado
                    const { data } = response;
                    if (JSON.stringify(data) === JSON.stringify(memoryContent)) {
                        setMemoryContent(data); // Actualizar el estado con los datos del servidor
                        localStorage.setItem("memoryContent", JSON.stringify(data)); 
                        // ActualizarlocalStorage
                    }
                })
                .catch((error) console.error("Error al cargar los datos:", error));
                };
                
                fetchData();

                const intervalId = setInterval(fetchData, 20000);

                // Limpiar el intervalo cuando el componente se desmonte
                return () clearInterval(intervalId);
                }, [memoryContent]);

    ```

8. __Recuperación de datos con Axios__

    en el `paht` se le pasa el id por paremtro que lo va a recibir en el componente memoryGame

    ```js
    <Route
    paht = "/memory/:id"
    elment = {<MemoryGame games ={memoryContent}/>}
    />
    ```

    Luego recibe un componente MemoryGame y hace un find para renderizar el id que se le paso por la url.


    ```js
        export const MemoryGame = ({games}) => {
        const id = useParams().id; //usamos el hook useParams para conseguir el id del paht y se lo asignamos a una constante
        const content = games.find((game) ==> game.id === id);
        }
    ```
    `const content = games.find((game) ==> game.id === id);` como el componente recibe todo el JSON de la BD como prop tenemos que hacer find ára que nos devuelva solo el juego que qeuremos renderizar.


9. __Crea un MemoryGame__

    ```js

        const handleSubmit = (e) => {
        e.preventDefault();
        
        axios.post("http://127.0.0.1:3001/create-memory-game", data).then((response) => {
        console.log(response.data);
        //hace un post en la url correspondiente y le pasa el objeto dara, despues resetea los datos
        
        setData({
            title: ''
            content: ''
            words: [],
        })
        setArrayText('')
        });
        };

    ```
