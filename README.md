//ESTRUTURA BÁSICA DE UM FLUTTER

import 'package:flutter/material.dart';

void main(){
  
  runApp(MaterialApp(
    
    title: "Trabalhando com imagens",
    home: Container(
      margin: EdgeInsets.only( top: 40),
      decoration: BoxDecoration(
        border: Border.all( width: 3,color: Colors.white)
        ),
      child: Image.asset(
        "images/mesa.jpg",
        fit: BoxFit.scaleDown,
        )
      ),
    
    ));
  
}
