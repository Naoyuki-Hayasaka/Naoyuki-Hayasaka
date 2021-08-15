### Hi there 👋

```javascript
import React, { useState } from "react";

export default function Naoyuki() {
  const [location, setLocation] = useState("Tokyo");
  const [job, setJob] = useState("Software Engineer");

  return (
    <div className="profile">
      <p>
        Hello, there! I am a {job} based in {location}.
      </p>
    </div>
  );
}

```
