### 1. Two Sum

#### 📝 Deskripsi

Diberikan sebuah larik (array) integer `nums` dan sebuah integer `target`, kembalikan **indeks dari dua angka** yang jika dijumlahkan akan menghasilkan `target`.

Asumsikan bahwa setiap input akan memiliki **tepat satu solusi**, dan Anda tidak boleh menggunakan elemen yang sama dua kali.

#### Cth.

- **Contoh 1:**

  - **Input:** `nums = [2, 7, 11, 15]`, `target = 9`
  - **Output:** `[0, 1]`
  - **Penjelasan:** Karena `nums[0] + nums[1] == 9`, kita kembalikan `[0, 1]`.

- **Contoh 2:**
  - **Input:** `nums = [3, 2, 4]`, `target = 6`
  - **Output:** `[1, 2]`

#### ⚠️ Batasan (Constraints)

- `2 <= nums.length <= 10^4`
- `-10^9 <= nums[i] <= 10^9`
- `-10^9 <= target <= 10^9`
- Hanya ada satu jawaban yang valid.

---

### 2. Remove Element

#### 📝 Deskripsi

Diberikan sebuah larik integer `nums` dan sebuah integer `val`, hapus semua kemunculan `val` dari `nums` secara **in-place** (tanpa membuat array baru). Urutan elemen yang tersisa tidaklah penting.

Kembalikan `k`, yaitu jumlah elemen yang tersisa setelah penghapusan.

#### Cth.

- **Contoh 1:**

  - **Input:** `nums = [3, 2, 2, 3]`, `val = 3`
  - **Output:** `2`, dan `nums` menjadi `[2, 2, _, _]`
  - **Penjelasan:** Fungsi Anda harus mengembalikan `k = 2`, dengan dua elemen pertama dari `nums` adalah 2. Isi array setelah indeks ke-2 tidak penting.

- **Contoh 2:**
  - **Input:** `nums = [0, 1, 2, 2, 3, 0, 4, 2]`, `val = 2`
  - **Output:** `5`, dan `nums` menjadi `[0, 1, 4, 0, 3, _, _, _]`

#### ⚠️ Batasan (Constraints)

- `0 <= nums.length <= 100`
- `0 <= nums[i] <= 50`
- `0 <= val <= 100`

---

### 3. Reverse String

#### 📝 Deskripsi

Tulis sebuah fungsi yang membalik sebuah string. String input diberikan sebagai sebuah larik karakter `char[]`.

Anda harus melakukan ini secara **in-place** (memodifikasi larik input secara langsung) dengan menggunakan memori tambahan $O(1)$.

#### Cth.

- **Contoh 1:**

  - **Input:** `s = ['h', 'e', 'l', 'l', 'o']`
  - **Output:** `['o', 'l', 'l', 'e', 'h']`

- **Contoh 2:**
  - **Input:** `s = ['H', 'a', 'n', 'n', 'a', 'h']`
  - **Output:** `['h', 'a', 'n', 'n', 'a', 'H']`

#### ⚠️ Batasan (Constraints)

- `1 <= s.length <= 10^5`
- `s[i]` adalah karakter ASCII yang dapat dicetak.

---

### 4. Contains Duplicate

#### 📝 Deskripsi

Diberikan sebuah larik integer `nums`, kembalikan `true` jika ada nilai yang muncul **setidaknya dua kali** di dalam larik, dan kembalikan `false` jika setiap elemennya unik.

#### Cth.

- **Contoh 1:**

  - **Input:** `nums = [1, 2, 3, 1]`
  - **Output:** `true`

- **Contoh 2:**
  - **Input:** `nums = [1, 2, 3, 4]`
  - **Output:** `false`

#### ⚠️ Batasan (Constraints)

- `1 <= nums.length <= 10^5`
- `-10^9 <= nums[i] <= 10^9`

---

### 5. Trapping Rain Water

#### 📝 Deskripsi

Diberikan `n` bilangan bulat non-negatif yang merepresentasikan peta elevasi di mana lebar setiap batang adalah 1, hitung berapa banyak air yang dapat ditampung setelah hujan.

#### Cth.

- **Contoh 1:**
  - **Input:** `height = [0, 1, 0, 2, 1, 0, 1, 3, 2, 1, 2, 1]`
  - **Output:** `6`
  - **Penjelasan:** Peta elevasi di atas (bagian hitam) dapat menampung 6 unit air hujan (bagian biru).

### Penjelasan Gambar

![rainwatertrap](./rainwatertrap.png)

- **Contoh 2:**
  - **Input:** `height = [4, 2, 0, 3, 2, 5]`
  - **Output:** `9`

#### ⚠️ Batasan (Constraints)

- `n == height.length`
- `1 <= n <= 2 * 10^4`
- `0 <= height[i] <= 10^5`
