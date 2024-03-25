import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());

}

class MyApp extends StatelessWidget {
  const MyApp

  ({super.key});


  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Column',
      home: HomePage(),
    );
  }
}

class HomePage extends StatelessWidget{
  const HomePage ({Key? key}): super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: [
              Container(
                width: 200,
                height: 100,
                margin: const EdgeInsets.all(15),
                decoration: BoxDecoration(
                  color: Colors.blue[300],
                  borderRadius: BorderRadius.circular(30),

                ),
                child: const Center(child:
                Text('1', style:
                TextStyle(color: Colors.white ,
                  fontSize: 32,
                ),

                )
                )
              ),

              Container(
                  width: 200,
                  height: 100,
                  margin: const EdgeInsets.all(15),
                  decoration: BoxDecoration(
                    color: Colors.blue[400],
                    borderRadius: BorderRadius.circular(30),

                  ),
                  child: const Center(child:
                  Text('2', style:
                  TextStyle(color: Colors.white,
                    fontSize: 32,
                  ),

                  )
                  )
              ),

              Container(
                  width: 200,
                  height: 100,
                  margin: const EdgeInsets.all(15),
                  decoration: BoxDecoration(
                    color: Colors.blue[500],
                    borderRadius: BorderRadius.circular(30),

                  ),
                  child: const Center(child:
                  Text('3', style:
                  TextStyle(color: Colors.white,
                    fontSize: 32,
                  ),

                  )
                  )
              ),

              Container(
                  width: 200,
                  height: 100,
                  margin: const EdgeInsets.all(15),
                  decoration: BoxDecoration(
                    color: Colors.blue[600],
                    borderRadius: BorderRadius.circular(30),

                  ),
                  child: const Center(child:
                  Text('4', style:
                  TextStyle(color: Colors.white,
                    fontSize: 32,
                  ),

                  )
                  )
              ),

              Container(
                  width: 200,
                  height: 100,
                  margin: const EdgeInsets.all(15),
                  decoration: BoxDecoration(
                    color: Colors.blue[700],
                    borderRadius: BorderRadius.circular(30),

                  ),
                  child: const Center(child:
                  Text('5', style:
                  TextStyle(color: Colors.white,
                    fontSize: 32,
                  ),

                  )
                  )
              ),
            ]

        ),

      ),

    );


  }
 }
