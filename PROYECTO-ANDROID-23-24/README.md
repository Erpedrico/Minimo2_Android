# Minimo2_Android

Para realizar el ejercicio 3 he creado un nuevo layout (activity_question) donde puedas poner la fecha, el titulo y el mensaje que quieras enviar. Despues he creado un QuestionActivity 
y un QuestionResponse, el Response es un constructor que contiene date, sender, message y title. Despues he hecho que QuestionActivity recoga la información de los
inputtext del question layout y que al clicar el boton enviar haga la función addPeticiones la cual esta colocada en la interfaz que estamos usando y lo que hace es enviar 
un QuestionResponse a /Peticiones/question. Si sale bien devuelve un succesfull y si no un error.
