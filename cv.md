# rsschool-cv
> # Bagitzhanova Ulpan

**Contact Info:** 
* Email: bagitzanovaulpan@gmail.com
* Skype:ULPAN BAGITZHANOVA
* Lindedin: Ulpan Serik

**Goal:** 
to become a senior frontend developer

**Skills:** 
HTML, CSS, Javascript, Java in Android Studio, Sql,Python

**Internship experience:** 

Summer 2019 - "TENGIZCHEVROIL LLP", IT Department, SharePoint group

Winter 2020 - "TENGIZCHEVROIL LLP", IT Department, telecommunication service group

**Volunteering experience:** 

Summer 2017 - Volunteer in international exhibition "EXPO 2017"

**Languages:** 

Kazakh, Russian, English(IELTS score - 6.5), Korean(A2)

**Education:**

2016-2020 L.N.Gumilyov Eurasian National University, Computer Science

**Recent project:**

Mobile application for medical assistance in Android Studio using Java

**Latest code example: Java**
```Java
i.putExtras(bundle);
TestActivity.this.finish(); startActivity(i); } else { updateQuestion(); }}
else { if (mQuestionNumber == QuestionLibrary.questions.length) {
Intent i = new Intent(TestActivity.this, ResultsActivity.class);
Bundle bundle = new Bundle();
bundle.putInt("finalScore", mScore);
i.putExtras(bundle);
TestActivity.this.finish();
startActivity(i); } else { updateQuestion(); } } } });
//Logic for false button
mFalseButton.setOnClickListener(new View.OnClickListener() {
@Override
public void onClick(View view) {
openFalse();
if(mAnswer == false) {
mScore++;
updateScore(mScore);
//perform check before you update the question
if (mQuestionNumber == QuestionLibrary.questions.length) {
Intent i = new Intent(TestActivity.this, ResultsActivity.class);
Bundle bundle = new Bundle();
bundle.putInt("finalScore", mScore);
i.putExtras(bundle);
TestActivity.this.finish();
startActivity(i); } else {
updateQuestion(); } }
else { if (mQuestionNumber == QuestionLibrary.questions.length) {
Intent i = new Intent(TestActivity.this, ResultsActivity.class);
Bundle bundle = new Bundle();
bundle.putInt("finalScore", mScore);
i.putExtras(bundle);
TestActivity.this.finish();
startActivity(i); } else { updateQuestion(); } } } });}
private void openDialog() {
AlertDialog.Builder builder = new AlertDialog.Builder(TestActivity.this);
builder.setMessage("Absolutely right!");
AlertDialog alert = builder.create();
alert.show(); }
private void openFalse() {
AlertDialog.Builder builder = new AlertDialog.Builder(TestActivity.this);
builder.setMessage("Answer is wrong. Try again.");
```
