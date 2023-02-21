# React

<h3>React serve para criar interfaces web  </h3>

React é uma biblioteca.


# Componentes
 - São isolados
 - Se furar um pneu não vai interferir no vidro do carro por exemplo
 
 - A roda não é um carro, porém quando junta todos os componentes em uma ordem lógica forma o carro. Pequenos pedaços que quando junta monta algo maior


# JSX
 - Habilidade de escrever código html dentro do javascrit

----- COMPONENTES FUNCIONAIS -----
 import React from 'react';
 function App(){
        return <h1>Componente Funcional</h1>;
 }

----- CLASSES -----
import React from 'react';
class App extends React.Component {
    render(){
        return <h1>Componente Funcional</h1>;
    }     
 }



--------------------------------------------------------------

PropTypes exporta uma variedade de validadores que podem ser usados para certificar que os dados que você recebe são válidos.

import PropTypes from 'prop-types';

Post.propTypes = {
    likes: PropTypes.number.isRequired,
};