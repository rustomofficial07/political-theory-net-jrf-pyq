# Contributing Guide - योगदान कैसे दें?

यह guide आपको बताएगी कि आप इस repository में कैसे प्रश्न और जानकारी जोड़ सकते हैं।

## 🎯 योगदान के प्रकार

1. **नए PYQ जोड़ना** - 2015-2025 के प्रश्न
2. **सुधार करना** - पहले से दिए गए प्रश्नों में सुधार
3. **व्याख्या जोड़ना** - उत्तरों की विस्तृत व्याख्या
4. **Documentation बेहतर करना** - README या अन्य files में सुधार

## 📝 Step-by-Step प्रक्रिया

### Step 1: Fork करें
अपने GitHub account पर repository को fork करें।

### Step 2: Clone करें
```bash
git clone https://github.com/YOUR_USERNAME/political-theory-net-jrf-pyq.git
cd political-theory-net-jrf-pyq
```

### Step 3: नई Branch बनाएँ
```bash
git checkout -b add-questions-topic-name
```

### Step 4: Changes करें

अपने changes को सही folder में करें। उदाहरण:

**File:** `01-Political-Philosophy/2015.md`

```markdown
## Year: 2015

### Question 1
**Topic:** Political Philosophy
**Question:** राजनीतिक दर्शन में "Social Contract" का क्या अर्थ है?

**Options:**
a) समाज और राज्य के बीच एक समझौता
b) केवल व्यापारिक समझौता
c) धार्मिक समझौता
d) सैन्य समझौता

**Answer:** a) समाज और राज्य के बीच एक समझौता

**Explanation:** 
Social Contract Theory के अनुसार, समाज और राज्य के बीच एक implicit agreement होता है। 
इसे Hobbes, Locke और Rousseau ने विस्तार से समझाया है।
यह लोकतांत्रिक प्रणाली का आधार है।

**Reference:**
- Hobbes: Leviathan
- Locke: Second Treatise of Government
- Rousseau: The Social Contract

---
```

### Step 5: Commit करें
```bash
git add .
git commit -m "Add Political Philosophy questions for 2015"
```

### Step 6: Push करें
```bash
git push origin add-questions-topic-name
```

### Step 7: Pull Request भेजें
GitHub पर जाएँ और Pull Request बनाएँ।

## ✅ Quality Guidelines (गुणवत्ता के नियम)

### प्रश्न जोड़ते समय:
1. ✓ **सही format** में लिखें
2. ✓ **Verified sources** से लें (official NET papers)
3. ✓ **Correct answer** सुनिश्चित करें
4. ✓ **Hindi और English दोनों** का उपयोग करें
5. ✓ **Reference books** mention करें
6. ✓ **Typos** न हों

### Markdown Formatting:
```markdown
### Question [Number]
**Topic:** [Topic Name]
**Question:** [प्रश्न का पाठ]

**Options:**
a) Option 1
b) Option 2
c) Option 3
d) Option 4

**Answer:** [सही उत्तर]

**Explanation:** 
[विस्तृत व्याख्या यहाँ]

**Reference:**
- Book/Source 1
- Book/Source 2

---
```

## 🔍 Review Process (समीक्षा प्रक्रिया)

1. आपका PR submitted होगा
2. Maintainer review करेंगे
3. अगर changes चाहिए तो बताया जाएगा
4. आप update करेंगे
5. Approved होने के बाद merge होगा

## 📌 महत्वपूर्ण नोट्स

- ❌ **Copy-paste न करें** - अपने शब्दों में लिखें
- ✓ **Credits दें** - अगर किसी से लिया है तो mention करें
- ✓ **Unique value add करें** - सिर्फ प्रश्न नहीं, व्याख्या भी दें
- ✓ **Respectful रहें** - Comments में विनम्र रहें

## 🎁 Recognition

- आपका नाम README में जोड़ा जाएगा
- Active contributors को special badge मिलेगा
- Community में आपकी मान्यता होगी

## ❓ सवाल या समस्या?

1. **Issues** section में अपना सवाल पूछें
2. **Discussions** में बातचीत करें
3. Email या DM से संपर्क करें

---

**Thank you for contributing! 🙏**

Happy Contributing! 🚀✨
