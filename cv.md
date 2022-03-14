# Anton Ivanov
##### Junior frontend developer

>The future belongs to those who believe in the beauty of their dreams.
Eleanor Roosevelt.

## Contacts

* __Location:__ St.Petersburg, Russia
* __Phone:__ +7 950-012-83-04
* __E-mail:__ <aivanov.mcu@gmail.com>
* __GitHub:__ [azazellospb](https://github.com/azazellospb)
* __LinkedIn:__ [anton-ivanov](linkedin.com/in/anton-ivanov-33a599217)

## About me 

For 10 years since graduating from the Saint-Petersburg State Marine Technical University with honor I successfully worked at the leading industrial enterprises of St. Petersburg. The pandemic period and accelerating digitalization forced me to re-prioritize in favor to move into the IT industry. Since 2021, first on my own, then with a tutor, I began to master front-end development based on JS. 

## Skills

* HTML
* CSS(Bootstrap, BEM)
* JavaScript (fundamentals)
* Git/GitHub
* Figma
* Winter CMS
* Primavera P6

## Code example
    function numberOfPairs(gloves)
    {
        let uniqueColors= [... new Set(gloves)];
        uniqueColors.sort();
        let internalArray = [...gloves].sort();
        let arr=[];
        for (let i=0; i<uniqueColors.length; i++) 
        {
            arr.push(0);
            for (let j=0; j<internalArray.length; j++)   
            { 
                if (uniqueColors[i]==internalArray[j]) arr[i]+=1;
            }
        }
        arr=arr.map(x=>Math.floor(x/2));
        const initialValue = 0;
        const sumWithInitial = arr.reduce((previousValue, currentValue) => previousValue + currentValue,initialValue);
        return sumWithInitial;
    }

## Work experience
* __Russian Maritime Register of Shipping__, _Feb 2018 - Jan 2022_
 Certified internal quality auditor, ISO 9001.
* __Siemens__, _Nov 2015 - Jan 2018_
 Senior production scheduler
* __Baltic Shipyard__, _Aug 2012 - Nov 2015_
 Senior production scheduler.
* __Intai__, _Sep 2011 - Jul 2012_
 Engineer

## Education
* __Saint-Petersburg State Marine Technical University__
    - Faculty of Ship Power Engineering and Automation, marine engineer, 2011
* __Saint-Petersburg State Polytechnic University__
    - Innovation Management, the Presidential program, 2015
* __Oracle University__
    - Primavera P6 course, 2017

## Languages
* __Russian__ - native
* __English__ - B1-B2
* __Polish__ - A2

## Citizenship
* __Citezenship__ - Russia
* __Permission to work__ - Russia, Poland

