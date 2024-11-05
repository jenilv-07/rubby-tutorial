# Data Types

## 📊 1. Numeric Types
   - **Integer**: Whole numbers, positive or negative.
   - **Float**: Numbers with decimal points.
   - **Rational**: Fractions represented as rational numbers.
   - **Complex**: Numbers with real and imaginary parts.

   ```ruby
   # Integer
   apples = 5
   puts apples  # Output: 5

   # Float
   temperature = 36.6
   puts temperature  # Output: 36.6

   # Rational
   slice_of_cake = Rational(1, 3)
   puts slice_of_cake  # Output: (1/3)

   # Complex
   complex_number = Complex(4, 7)
   puts complex_number  # Output: (4+7i)
   ```

---

## ✨ 2. String
   - A sequence of characters used to represent text.

   ```ruby
   greeting = "Hello, World!"
   name = "Ruby"
   puts greeting  # Output: Hello, World!
   puts name      # Output: Ruby
   ```

---

## 🔖 3. Symbol
   - An immutable identifier, often used as keys in hashes or for lightweight identifiers.

   ```ruby
   status = :active
   puts status  # Output: active
   ```

---

## ✅ 4. Boolean
   - Represents true or false values.

   ```ruby
   is_ruby_fun = true
   puts is_ruby_fun  # Output: true

   is_javascript_hard = false
   puts is_javascript_hard  # Output: false
   ```

---

## 🚫 5. Nil
   - Represents "nothing" or "no value".

   ```ruby
   no_value = nil
   puts no_value  # Output: (prints nothing as it's nil)
   ```

---

## 📚 6. Array
   - An ordered list of elements that can be any data type.

   ```ruby
   # Numbers array
   numbers = [1, 2, 3, 4, 5]
   puts numbers  # Output: [1, 2, 3, 4, 5]

   # Mixed array
   mixed_array = [true, "Ruby", 3.14]
   puts mixed_array  # Output: [true, "Ruby", 3.14]
   ```

---

## 🗂 7. Hash
   - A collection of key-value pairs.

   ```ruby
   person = { name: "Alice", age: 25 }
   puts person  # Output: {:name=>"Alice", :age=>25}

   number_words = { 1 => "one", 2 => "two" }
   puts number_words  # Output: {1=>"one", 2=>"two"}
   ```

---

## 📏 8. Range
   - Represents a sequence of values, with a defined start and end.

   ```ruby
   inclusive_range = (1..5)
   puts inclusive_range.to_a  # Output: [1, 2, 3, 4, 5]

   exclusive_range = (1...5)
   puts exclusive_range.to_a  # Output: [1, 2, 3, 4]
   ```

---

## 🕰 9. Time
   - Used to represent and manipulate dates and times.

   ```ruby
   current_time = Time.now
   puts current_time  # Output: (current date and time)
   ```

---

## 📂 10. File
   - Used for reading and writing to files.

   ```ruby
   # Write to a file
   File.open("example.txt", "w") { |file| file.write("Hello, File!") }

   # Read from a file
   content = File.read("example.txt")
   puts content  # Output: Hello, File!
   ```

---

## 🔍 11. Regular Expressions (Regexp)
   - Used for pattern matching within strings.

   ```ruby
   text = "My phone number is 123-456-7890"
   match = text.match(/\d{3}-\d{3}-\d{4}/)
   puts match  # Output: 123-456-7890
   ```

