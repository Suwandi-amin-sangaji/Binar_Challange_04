# Binar: Challenge 04
# Suwandi Amin Sangaji
# Universitas Muhammadiyah Sorong

- Mulai modifikasi file `server/index.js` apabila ingin membuat HTTP server.
- Mulai modifikasi folder `public` apabila ingin memodifikasi HTML.

# `Binar` class

Class ini berisi 1 static method saja, yang berfungsi untuk mengambil data mobil dari internet.

```typescript
interface Car {
  id: string;
  plate: string;
  manufacture: string;
  model: string;
  image: string;
  rentPerDay: number;
  capacity: number;
  description: string;
  transmission: string;
  available: boolean;
  type: string;
  year: string;
  options: Array<string>;
  specs: Array<string>;
}

interface Binar {
  listCars(filterer: (car: Car) => boolean): Array<Car>
}
```

Method `listCars` ini akan menerima fungsi yang mana harus mengembalikan `boolean` sebagai nilainya. 
Fungsi ini akan dijalankan untuk masing-masing item di dalam list of cars, yang mana jika nilainya `true`,
maka akan ditampilkan di dalam list tersebut.

# Tips

Just, hack it bro!

# View
  ![Screen Shot 2022-04-10 at 19 04 26](https://user-images.githubusercontent.com/61943487/162613409-afc3c9bc-bf1c-42ce-9451-558293f68574.png)

![Screen Shot 2022-04-10 at 19 14 56](https://user-images.githubusercontent.com/61943487/162613443-c8e52a45-d1a1-488d-8599-413fe65bf6bd.png)
