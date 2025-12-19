# Ex09 Event Registration Web Application
## Date:19.12.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
import React from "react";
import logo1 from "./logo-1.png";
import photo1 from "./photo-1.png";

export const AndroidMedium = (): JSX.Element => {
  return (
    <main className="flex h-[840px] items-center gap-2.5 relative bg-[#e6eed6] w-full min-w-[700px]">
      <img
        className="relative w-[700px] h-[840px] aspect-[1] object-cover"
        alt="Background photo with colorful stage lighting"
        src={photo1}
      />

      <div className="absolute top-11 left-[29px] w-[641px] h-32 aspect-[5.01]" />

      <h1 className="absolute top-[237px] left-[calc(50.00%_-_277px)] w-[597px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-8xl tracking-[0] leading-[normal] whitespace-nowrap">
        DRESTEIN-26
      </h1>

      <img
        className="absolute top-11 left-[calc(50.00%_-_287px)] w-[575px] h-[142px] aspect-[4.05] object-cover"
        alt="Saveetha Engineering College logo"
        src={logo1}
      />

      <p className="absolute top-[457px] left-[190px] w-[322px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-[#cfb1b1] text-5xl tracking-[0] leading-[normal] whitespace-nowrap">
        COMING SOON
      </p>
    </main>
  );
};
import React from "react";
import x221 from "./22-1.png";
import LOGODE1 from "./LOGODE-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const AndroidMedium = (): JSX.Element => {
  const leftDepartments = ["CSE", "EEE", "ECE", "AGRI", "EIE"];
  const rightDepartments = ["MECH", "CIVIL", "BIO MED", "CHEM", "IT"];
  const eventsList = ["WORKSHOPS", "HACKATHON"];
  const rightEventsList = ["PAPER PRESENTATTION", "PROJECT DISPLAY"];

  return (
    <main className="bg-white w-full min-w-[700px] min-h-[840px] relative">
      <img
        className="absolute top-0 left-0 w-[700px] h-[840px] aspect-[1.5] object-cover"
        alt="Background"
        src={x221}
      />

      <nav
        className="absolute top-[119px] left-[67px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]"
        aria-label="Left departments"
      >
        {leftDepartments.map((dept, index) => (
          <React.Fragment key={dept}>
            {dept}
            {index < leftDepartments.length - 1 && <br />}
          </React.Fragment>
        ))}
      </nav>

      <section className="absolute top-[594px] left-[47px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-[#fffafa] text-[32px] tracking-[0] leading-[normal]">
        TECHNICAL EVENTS
      </section>

      <nav
        className="absolute top-[119px] right-[19px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]"
        aria-label="Right departments"
      >
        {rightDepartments.map((dept, index) => (
          <React.Fragment key={dept}>
            {dept}
            {index < rightDepartments.length - 1 && <br />}
          </React.Fragment>
        ))}
      </nav>

      <img
        className="absolute top-[94px] left-52 w-[300px] h-[66px]"
        alt="Decorative text on path"
        src={textOnAPath}
      />

      <p className="absolute top-[329px] left-[calc(50.00%_-_114px)] w-[340px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-[#45d52f] text-[32px] tracking-[0] leading-[normal]">
        <br />
        WIN ATTRACTIVE PRIZES WORTH
        <br />
        ₹10 LAKHS
      </p>

      <h2 className="absolute top-[541px] left-[274px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-[#ff0000] text-[32px] tracking-[0] leading-[normal]">
        EVENTS
      </h2>

      <div className="absolute top-[652px] left-[301px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]">
        {rightEventsList[0]}
      </div>

      <div className="absolute top-[714px] left-[296px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]">
        {rightEventsList[1]}
      </div>

      <div className="absolute top-[683px] left-[47px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]">
        {eventsList[0]}
      </div>

      <h1 className="absolute top-[31px] left-[calc(50.00%_-_216px)] w-[433px] [font-family:'Kavoon-Regular',Helvetica] font-normal text-white text-[64px] tracking-[0] leading-[normal] whitespace-nowrap">
        DRESTEIN-26
      </h1>

      <img
        className="absolute top-[127px] left-[calc(50.00%_-_83px)] w-[167px] h-[166px] aspect-[1] object-cover"
        alt="Drestein logo"
        src={LOGODE1}
      />

      <div className="absolute top-[753px] left-[47px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-white text-[32px] tracking-[0] leading-[normal]">
        {eventsList[1]}
      </div>
    </main>
  );
};
import React from "react";
import regi1 from "./regi-1.png";

export const Image = (): JSX.Element => {
  return (
    <div className="w-[2320px] h-[1546px]">
      <img
        className="fixed top-[59px] left-[1172px] w-[651px] h-[781px] aspect-[1.5] object-cover"
        alt="Regi"
        src={regi1}
      />
    </div>
  );
};
```

## OUTPUT:

![alt text](<Screenshot 2025-12-19 161143.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
