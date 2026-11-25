**import os**



**base = "DATA ANALYST\_PROJECT'S"**

**folders = \["DATA ANALYST\_FINAL PROJECT", "DATA ANALYST\_PROJECT 1", "DATA ANALYST\_PROJECT 2", "DATA ANALYST\_PROJECT 3"]**

**bang = chr(33)**



**for folder in folders:**

&#x20;   **p = os.path.join(base, folder, "README.md")**

&#x20;   **lines = open(p, encoding="utf-8").readlines()**

&#x20;   **out, n = list(), 1**

&#x20;   **for l in lines:**

&#x20;       **out.append(l)**

&#x20;       **if ("Visualization " in l or "Chart " in l) and "—" in l:**

&#x20;           **out.append(f"{bang}\[Chart {n}](screenshots/chart\_{n}.png)\\n")**

&#x20;           **n += 1**

&#x20;   **open(p, "w", encoding="utf-8").writelines(out)**

&#x20;   **print(f"Fixed {n-1} images in {folder}")**



