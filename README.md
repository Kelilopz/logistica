ruta.json :{
    "name": "bucaramanga-bogota",
    "vehicle": {
            placa: "ebn465",
            modelo: "2016",
            capacity_carga:"10",
            sucursal_id: #####,
            marca: "BMW",
            description: "una descripcion sobre la ruta",
            conductor:{
                name: "Kelly Lopez",
                phone: 3052288509
            } 
            auxiliar:{
                name:"Darwin Fernandez",
                phone: 3052397584
            }         
    }
}

envios.json :{
    id: "1",
    cliente_id: "1",
    paquete_id: "1",
    fecha_envio: 23-05-2024 4:000:00,
    destino: id_ciudad,
    ruta_id: id ruta,
    sucursal_id: id sucursal,     
}


pais.json :{
    id: "1",
    name: "Colombia"
}
ciudad.json :{
    id: "1",
    name: "Bucaramanga"
}

sucursal.json :{
    id: "1",
    country_id: "1",
    city_id: "1",
    direction: "calle 105#9-98 provenza",
    name: "Bucaramanga Centro"
}

cliente.json :{
    id: "1",
    name: "David Perez",
    email: "david@gmail.com",
    direction: "diagonal 14c #57-59",
    phone: [3124013599,607658987]
}


paquetes.json:{
    numero_seguimiento: 34523434,
    peso: 10 
    dimesiones: {
        largo: 20,
        ancho: 10,
        alto: 5 
    }
    contenido: "descripcion del contenido"
    valor declarado: 40000,
    tipo_servicio: envio ,
    estado: "en camino",
    seguimiento: {
        ubicacion: "calle 23 #154-20",
        fecha_hora: 03-08-2023 04:39:00
    }

}

