# Family Tree Member Addition Guide

## 📝 How to Add New Family Members

### **Template for Adding Family Members**

Copy and paste this template to add new family members to the HTML:

```html
<!-- Person Template -->
<div class="person-card">
  <img src="images/[photo-name].jpg" alt="[Person Name] photo" />
  <h3>[Full Name]</h3>
  <p>Born: [Date of Birth]</p>
  <p>Spouse: [Spouse Name or <span class="to-be-added">To be added</span>]</p>
  <p>Children: [Children Names or <span class="to-be-added">To be added</span>]</p>
</div>

<!-- Spouse Template (if married) -->
<div class="person-card">
  <img src="images/[spouse-photo-name].jpg" alt="[Spouse Name] photo" />
  <h3>[Spouse Full Name]</h3>
  <p>Spouse of [Partner Name]</p>
</div>

<!-- Unmarried Person with Spouse Placeholder -->
<div class="person-card">
  <img src="images/[photo-name].jpg" alt="[Person Name] photo" />
  <h3>[Full Name]</h3>
  <p>Born: [Date of Birth]</p>
  <p>Spouse: <span class="to-be-added">To be added</span></p>
</div>
<div class="person-card spouse-placeholder">
  <img src="images/spouse-placeholder.jpg" alt="Spouse placeholder" />
  <h3><span class="to-be-added">Spouse of [Person Name]</span></h3>
  <p>Add photo and name</p>
</div>
```

### **How to Add New Generations**

```html
<div class="generation-title">[Generation Name]</div>
<div class="tree-level">
  [Add person cards here]
</div>
```

### **How to Add New Children Groups**

```html
<div class="children-group">
  <h3>Children of [Parent Name]</h3>
  <div class="tree-level">
    [Add children person cards here]
  </div>
</div>
```

## 📸 Photo Naming Convention

Use these naming patterns for photos:
- **Family members**: `[first-name].jpg` (e.g., `john.jpg`)
- **Spouses**: `[first-name]-[last-name].jpg` (e.g., `jane-smith.jpg`)
- **Children with same names**: `[name]-[birth-year].jpg` (e.g., `john-2005.jpg`)
- **Family photos**: `family-photo-[number].jpg` (e.g., `family-photo-5.jpg`)

## 🎯 Current Structure

### **First Generation**
- Simon Murambidzi ✓
- Maggie Dahwa ✓

### **Second Generation** 
- Phillip Murambidzi (Snr) ✓
- Sabina Marhanele ✓

### **Children of Phillip & Sabina**
- Shepherd Murambidzi ✓ (Spouse: Cynthia Madzimbira ✓)
- Emeldah Murambidzi ✓ (Spouse: To be added)
- Tendai Murambidzi ✓ (Spouse: Amanda Murambidzi ✓)
- Peter Murambidzi ✓ (Spouse: To be added)
- Phillip Murambidzi (Jnr) ✓ (Spouse: To be added)
- Winnet Murambidzi ✓ (Spouse: To be added)
- Simeon Murambidzi ✓ (Spouse: To be added)
- Tafadzwa Murambidzi ✓ (Spouse: To be added)

### **Grandchildren**
- Children of Shepherd ✓
- Children of Emeldah ✓
- Children of Tendai ✓

## 🔄 Easy Update Process

1. **Edit index.html** on GitHub
2. **Copy template** and replace bracketed text
3. **Upload photos** to images/ folder
4. **Commit changes** to update website

The website automatically updates within 1-2 minutes!
