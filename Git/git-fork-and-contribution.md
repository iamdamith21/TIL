# Git Fork සහ Open Source Contribution

Fork එකක් භාවිතා කරන්නේ වෙනත් අයෙකුගේ ව්‍යාපෘතියකට (Project) හානියක් නොකර වෙනස්කම් සිදු කිරීමටයි.

### Fork කිරීමේ පියවර (Workflow):
1. **Fork:** GitHub හි අදාළ Project එකට ගොස් දකුණු පස ඉහළ ඇති "Fork" බටන් එක ක්ලික් කරන්න. දැන් එම Project එක ඔබේ GitHub ගිණුමට ලැබෙනු ඇත.
2. **Clone:** ඔබේ ගිණුමට ලැබුණු එම Fork එක ඔබේ පරිගණකයට බාගත කරන්න.
   `git clone https://github.com/your-username/project-name.git`
3. **Branch:** වෙනස්කම් සිදු කිරීමට අලුත් Branch එකක් සාදන්න.
   `git checkout -b my-feature`
4. **Push:** ඔබේ වෙනස්කම් සිදු කර ඔබේ GitHub ගිණුමට (Fork එකට) Push කරන්න.
5. **Pull Request (PR):** මුල් අයිතිකරුගේ Repository එකට ඔබේ වෙනස්කම් ඇතුළත් කරන ලෙස ඉල්ලීමක් කරන්න.

### Fork කිරීම වැදගත් වන්නේ ඇයි?
- මුල් Project එකේ Code එකට කෙලින්ම වෙනස්කම් කිරීමට ඔබට අවසර (Permission) නොමැති විට Fork කිරීම අත්‍යවශ්‍ය වේ.
- ඔබට අවශ්‍ය පරිදි අත්හදා බැලීම් කිරීමට නිදහස ලැබේ.