## **Step-by-Step Process for Sorting Non-Bottle Glass Using Available Sensors**

### **Step 1: Initial Identification (Image Recognition)**

1. **Image recognition** identifies the object as **glass** based on its shape and common glass items (e.g., drinking glasses, glass jars, glassware).
   - The system can recognize basic forms of **non-bottle glass** waste, such as **drinking glasses**, **jars**, and **glass cookware**.

2. **Display prompts the user** if the glass item has mixed materials (e.g., plastic lids or metal handles attached to the glass). The user may be asked to remove these components before proceeding.

---

### **Step 2: Optical Sensors for Color Detection**

1. The system uses **optical sensors** to detect the **color of the glass** (clear, green, brown). This step is more relevant if color sorting is needed for recycling purposes:
   - **Clear glass** (e.g., drinking glasses, jars).
   - **Green or brown glass** (typically seen in decorative glass or cookware).

2. **System Feedback**:
   - If color sorting is required, the system will prompt the user to place the item in the appropriate bin based on color:
     - **Clear glass**: "Place in the 'Clear Glass Recycling' bin."
     - **Green or brown glass**: "Place in the 'Colored Glass Recycling' bin."
   - If color sorting is not needed, the system skips this step.

---

### **Step 3: Condition Detection (Intact or Broken)**

1. The system uses **cameras and optical sensors** to assess whether the glass is **intact** or **broken**:
   - **Intact Glass**: Items like **drinking glasses** or **glass jars** that are undamaged and reusable.
   - **Broken Glass**: Items that are chipped, cracked, or shattered.

2. **System Feedback**:
   - If the glass is **intact** and usable, the system directs the user to place it in the **second-hand reuse bin** for potential resale or reuse.
     - **System Message**: "This item is in good condition. Place it in the 'Second-Hand Glass' bin."
   - If the glass is **broken** or damaged beyond reuse, the system directs the user to place it in the **glass recycling bin**.
     - **System Message**: "This item is damaged. Place it in the 'Glass Recycling' bin."

---

### **Step 4: Weight Sensor (Optional)**

1. **Weight sensors** can be used to distinguish between heavier glass items (e.g., cookware) and lighter glass (e.g., drinking glasses or jars).
   - For example, **glass cookware** tends to be thicker and heavier than **drinking glasses**, so the weight sensor can confirm this difference.

2. **System Feedback**:
   - If the item is heavier (e.g., glass cookware), the system can prompt the user to handle it with care and direct it to the appropriate bin for recycling.
     - **System Message**: "This is a heavier glass item, place it carefully in the 'Heavy Glass Recycling' bin."

---

### **Step 5: Final Sorting**

1. Based on the condition (intact or broken), color, and weight (optional) of the glass, the system directs the user to place the item in the appropriate bin:
   - **Second-Hand Glass**: Intact drinking glasses, jars, or reusable glass items.
   - **Recycling**:
     - **Clear Glass**: If color sorting is implemented, the system directs clear glass to the appropriate recycling bin.
     - **Colored Glass (Green/Brown)**: Directed to the colored glass recycling bin if applicable.
     - **Broken Glass**: Any damaged or broken glass items are directed to the general glass recycling bin.

---
