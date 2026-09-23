# unicvt
A C++20 encoding library (header-only)
___
### Features:
- `uni::string` class
- `unicvt<encoding>(target)` function
- interpolability of/compatibility with `std::string`, `std::u8string`, `std::u16string`, `std::u32string`, `std::wstring` via `uni::string`
- legacy encodings support
- `std::formatter` specialisations for string types
- `std::[w]cout::operator<<` overload for `uni::string`