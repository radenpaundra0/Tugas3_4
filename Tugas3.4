import 'package:flutter/material.dart';

void main() {
  runApp(const FoodApp());
}

class FoodApp extends StatelessWidget {
  const FoodApp({super.key});

  @override
  Widget build(BuildContext context) {
    return const MaterialApp(
      debugShowCheckedModeBanner: false,
      home: LoginPage(),
    );
  }
}

class LoginPage extends StatelessWidget {
  const LoginPage({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Container(
        decoration: const BoxDecoration(
          gradient: LinearGradient(
            colors: [Colors.orange, Colors.deepOrange],
            begin: Alignment.topCenter,
            end: Alignment.bottomCenter,
          ),
        ),
        child: Center(
          child: Card(
            elevation: 8,
            shape: RoundedRectangleBorder(
              borderRadius: BorderRadius.circular(20),
            ),
            child: Padding(
              padding: const EdgeInsets.all(24),
              child: Column(
                mainAxisSize: MainAxisSize.min,
                children: [
                  const Icon(Icons.fastfood, size: 80, color: Colors.orange),
                  const SizedBox(height: 20),
                  const Text(
                    "Food Order App",
                    style: TextStyle(fontSize: 22, fontWeight: FontWeight.bold),
                  ),
                  const SizedBox(height: 20),
                  const TextField(
                    decoration: InputDecoration(
                      labelText: "Username",
                      border: OutlineInputBorder(),
                    ),
                  ),
                  const SizedBox(height: 15),
                  const TextField(
                    obscureText: true,
                    decoration: InputDecoration(
                      labelText: "Password",
                      border: OutlineInputBorder(),
                    ),
                  ),
                  const SizedBox(height: 20),
                  ElevatedButton(
                    style: ElevatedButton.styleFrom(
                      backgroundColor: Colors.orange,
                      minimumSize: const Size(double.infinity, 45),
                    ),
                    onPressed: () {
                      Navigator.push(
                        context,
                        MaterialPageRoute(
                          builder: (context) => const HomePage(),
                        ),
                      );
                    },
                    child: const Text("Login"),
                  ),
                ],
              ),
            ),
          ),
        ),
      ),
    );
  }
}

class HomePage extends StatelessWidget {
  const HomePage({super.key});

  final List<Map<String, dynamic>> foods = const [
    {"name": "Burger", "price": 25000, "icon": Icons.lunch_dining},
    {"name": "Pizza", "price": 50000, "icon": Icons.local_pizza},
    {"name": "Fried Rice", "price": 20000, "icon": Icons.rice_bowl},
  ];

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text("Menu Makanan"),
        backgroundColor: Colors.orange,
      ),
      body: ListView.builder(
        padding: const EdgeInsets.all(16),
        itemCount: foods.length,
        itemBuilder: (context, index) {
          final food = foods[index];
          return Card(
            margin: const EdgeInsets.only(bottom: 15),
            elevation: 5,
            child: ListTile(
              leading: Icon(food["icon"], size: 40, color: Colors.orange),
              title: Text(food["name"]),
              subtitle: Text("Rp ${food["price"]}"),
              trailing: const Icon(Icons.arrow_forward_ios),
              onTap: () {
                Navigator.push(
                  context,
                  MaterialPageRoute(
                    builder: (context) => DetailPage(food: food),
                  ),
                );
              },
            ),
          );
        },
      ),
    );
  }
}

////////////////////////////////////////////////////////////
/// DETAIL PAGE
////////////////////////////////////////////////////////////

class DetailPage extends StatelessWidget {
  final Map<String, dynamic> food;

  const DetailPage({super.key, required this.food});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text(food["name"]),
        backgroundColor: Colors.deepOrange,
      ),
      body: Padding(
        padding: const EdgeInsets.all(20),
        child: Column(
          children: [
            Icon(food["icon"], size: 120, color: Colors.orange),
            const SizedBox(height: 20),
            Text(
              food["name"],
              style: const TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
            ),
            const SizedBox(height: 10),
            Text(
              "Harga: Rp ${food["price"]}",
              style: const TextStyle(fontSize: 18),
            ),
            const Spacer(),
            ElevatedButton(
              style: ElevatedButton.styleFrom(
                backgroundColor: Colors.deepOrange,
                minimumSize: const Size(double.infinity, 50),
              ),
              onPressed: () {
                Navigator.push(
                  context,
                  MaterialPageRoute(
                    builder: (context) => PaymentPage(price: food["price"]),
                  ),
                );
              },
              child: const Text("Pesan Sekarang"),
            ),
          ],
        ),
      ),
    );
  }
}

////////////////////////////////////////////////////////////
/// PAYMENT PAGE
////////////////////////////////////////////////////////////

class PaymentPage extends StatelessWidget {
  final int price;

  const PaymentPage({super.key, required this.price});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text("Pembayaran"),
        backgroundColor: Colors.green,
      ),
      body: Padding(
        padding: const EdgeInsets.all(20),
        child: Column(
          children: [
            const Icon(Icons.payment, size: 100, color: Colors.green),
            const SizedBox(height: 20),
            Text(
              "Total Pembayaran",
              style: const TextStyle(fontSize: 20, fontWeight: FontWeight.bold),
            ),
            const SizedBox(height: 10),
            Text(
              "Rp $price",
              style: const TextStyle(fontSize: 24, color: Colors.green),
            ),
            const Spacer(),
            ElevatedButton(
              style: ElevatedButton.styleFrom(
                backgroundColor: Colors.green,
                minimumSize: const Size(double.infinity, 50),
              ),
              onPressed: () {
                showDialog(
                  context: context,
                  builder: (_) => AlertDialog(
                    title: const Text("Sukses"),
                    content: const Text("Pesanan Anda berhasil diproses!"),
                    actions: [
                      TextButton(
                        onPressed: () {
                          Navigator.pop(context);
                          Navigator.popUntil(context, (route) => route.isFirst);
                        },
                        child: const Text("OK"),
                      ),
                    ],
                  ),
                );
              },
              child: const Text("Bayar Sekarang"),
            ),
          ],
        ),
      ),
    );
  }
}
