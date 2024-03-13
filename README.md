# rust-practice-trait-object-and-associated-type

### Gồm các kiến thức sau: 

1. Kiểu dữ liệu
2. Struct
3. Trait (trait bound, associated type)
4. Generic Type 
5. Viết unit tests (cách sử dụng `assert_eq!` để so sánh kết quả thực tế và kết quả mong muốn)

Ví dụ :
+ Định nghĩa viết test case 
```rust
// định nghĩa viết test case 
#[cfg(test)]
mod tests {
    // unit test 
    #[test]
	fn one_greater_than_zero() {
        assert!(1>0, "1 lớn hơn 0");
    }
    #[test]
	fn one_equal_one() {
        assert_eq!(1, 1);
    }
}
```

+ Chạy test bằng `cargo test`

### Implementation

+ Đọc hiểu nội dung của logic 
+ Hoàn thành `todo!()`

### Run test

```bash
cargo test 
```
