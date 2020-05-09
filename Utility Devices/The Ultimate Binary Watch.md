### The Ultimate Binary Watch
This project involves a sort of stylish binary watch which can perform multiple functions like time, date, alarm, USB charnging, etc.

**Components used:**
1. [APA102](https://hyperion-project.org/attachments/apa102_led-pdf.102/) LED (these are relatively small)
2. [Atmega328P-AU](https://www.alldatasheet.com/view.jsp?Searchword=Atmega328p%20datasheet&gclid=EAIaIQobChMI1pXIzvKm6QIVz34rCh2kog5pEAAYASAAEgJj8vD_BwE) microcontroller
3. [M41T62](https://www.alldatasheet.com/view.jsp?Searchword=M41t62&gclid=EAIaIQobChMI3dDE1_Km6QIVlzMrCh1phwsfEAAYASAAEgLGH_D_BwE) RTC
4. [TPS61220](https://www.alldatasheet.com/view.jsp?Searchword=Tps61220%20Datasheet&gclid=EAIaIQobChMImLKQ6fKm6QIVWyQrCh3KyguUEAAYASAAEgIb-_D_BwE)
5. Turnigy nano-tech 300mAh 1S battery
6. [MCP73831T](https://www.alldatasheet.com/view.jsp?Searchword=Mcp73831t%20datasheet&gclid=EAIaIQobChMI15L0g_Om6QIVmB0rCh2PtAQ6EAAYASAAEgJpC_D_BwE) charging IC
7. [BQ29700](https://www.alldatasheet.com/view.jsp?Searchword=Bq2970&gclid=EAIaIQobChMIkLXykvOm6QIVSiUrCh2XRAeEEAAYASAAEgKtTvD_BwE) IC for LiPo protection

![Design](https://content.instructables.com/FFY/T59P/K9ACO5LN/FFYT59PK9ACO5LN.LARGE.jpg?auto=webp&frame=1&width=1024&fit=bounds)

**The design:**
* USB port used to charge LiPo batteries through a 'LiPo protection circuit'
* DC-DC boost convertor TPS61220 used to satisfy RTC(max 4.5V) and microcontroller(min 4.5V)
* The microcontroller handles the output and input in reference to the RTC.\
* Required codes are uploaded after 3D printing and assembly of parts.
* Watch reads in Binary coded decimal(BCD) :

![BCD explanation](https://content.instructables.com/FY5/SR64/K9D1XSHQ/FY5SR64K9D1XSHQ.LARGE.jpg?auto=webp&frame=1&width=1024&height=1024&fit=bounds)

**Full Story** with greater description and diagrams can be found [here](https://www.instructables.com/id/The-Ultimate-Binary-Watch/)

**Additional Comments:** More features could be added to it, but there's space contstraints assosciated with it. Further, BCD is a good way to show digits and can be extended to various other projects.
