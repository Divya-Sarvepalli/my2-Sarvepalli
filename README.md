# my2-Sarvepalli
My Second Repo, Lab 2
# Divya Sarvepalli
###### Vacation Spot : Ooty
I love Ooty because of the **climate**. It always have the low temperature and the **nature** was so soothing, **greenary** after the rain was the best. Also, it's famous for **Tea Estates** where the original and natural tea is prepared. Serving a fresh hot tea with cool climate makes a perfect evening.

---

### Activities I do at my Vacation Spot:
1. Click pictures of nature.
2. Listen to music to enjoy the vibe.
3. Get to know more about speciality/highlights of that place.

### Dishes of food that are famous at my Vacation Spot:
* Ooty Varkey
* Neer Dosa
* Chicken Chettinad


[MyStats Link](MyStats.md)

---

### Sports that you must try Once!
I'm not a sports person but there are some sports which everyone should try atleast once. Because, it's beginner friendly and builds confidence so that we may enter into the ***Sports World!***

| Sports Name | Why to play | Hours per week |
| --- | --- | :---: |
| Badminton | Beginner Friendly | 3 |
| Swimming | Improves Flexibility  | 2 |
| Cycling | cardiovascular fitness  | 2 |
| Running | builds strong bones | 5 |

---

> ### 2 quotes by Scientists that I like:
>
> - “Everything is theoretically impossible until it is done.” – ***Robert A. Heinlein***
>
> - “If we knew what it was we were doing, it would not be called research, would it?” – ***Albert Einstein***
>


---

'''
@function is-number($value) {
  @return type-of($value) == 'number';
}
 
@function is-time($value) {
  @return is-number($value) and index('ms' 's', unit($value)) != null;
}
 
@function is-duration($value) {
  @return is-time($value);
}
 
@function is-angle($value) {
  @return is-number($value) and index('deg' 'rad' 'grad' 'turn', unit($value)) != null;
}
 
@function is-frequency($value) {
  @return is-number($value) and index('Hz' 'kHz', unit($value)) != null;
}
 
@function is-integer($value) {
  @return is-number($value) and round($value) == $value;
}
 
@function is-relative-length($value) {
  @return is-number($value) and index('em' 'ex' 'ch' 'rem' 'vw' 'vh' 'vmin' 'vmax', unit($value)) != null;
}
 
@function is-absolute-length($value) {
  @return is-number($value) and index('cm' 'mm' 'in' 'px' 'pt' 'pc', unit($value)) != null;
}
 
@function is-percentage($value) {
  @return is-number($value) and unit($value) == '%';
}
 
@function is-length($value) {
  @return is-relative-length($value) or is-absolute-length($value);
}
 
@function is-resolution($value) {
  @return is-number($value) and index('dpi' 'dpcm' 'dppx', unit($value)) != null;
}
 
@function is-position($value) {
  @return is-length($value) or is-percentage($value) or index('top' 'right' 'bottom' 'left' 'center', $value) != null;
} 
'''


