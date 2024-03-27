# Terst
 import 'package:flutter/material.dart';

void main() {
  runApp(MeuApp());
}

class MeuApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Bem-vindo ao Flutter',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Bem-vindo ao Flutter'),
        ),
        body: Center(
          child: Text('Olá, Mundo!'),
        ),
      ),
    );
  }
}

