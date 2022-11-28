# ASSIGNMENT #09: Portfolio

##### _By Vicky Jen| DH110: User Experience and Design_

1. Heuristic Evaluation: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT01
2. Usability Testing: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT02
3. Contextual Inquiry: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT03
4. User Persona/Scenario: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT04
5. Lo-fi Prototype: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT%2005
6. Interface Design: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT06
7. Hi-Fi Prototype: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT07

.container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  overflow-x: hidden;
  align-items: center;
  flex-direction: column;
  background-color: #0F0F0F;
}
.section {
  width: 100%;
  height: 80vh;
  display: flex;
  align-items: center;
  border-color: #51515A;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  border-bottom-width: 1px;
}
.hero {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.content {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
}
.main {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.header {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.heading {
  color: rgb(255, 255, 255);
  font-size: 64px;
  align-self: flex-start;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.caption {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-family: Poppins;
  line-height: 30px;
}
.buttons {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.get-started {
  display: flex;
  background-color: #80FF44;
}
.text03 {
  color: #0C100C;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.get-started1 {
  background-color: #2A2A2A;
}
.text04 {
  color: #ffffff;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.highlight {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.avatars {
  width: 115px;
  height: var(--dl-size-size-small);
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: row;
}
.image {
  left: 0px;
  position: absolute;
}
.image01 {
  left: var(--dl-space-space-twounits);
  position: absolute;
  object-fit: cover;
}
.image02 {
  left: var(--dl-space-space-fourunits);
  position: absolute;
  object-fit: cover;
}
.caption1 {
  color: rgb(255, 255, 255);
  font-family: Poppins;
  line-height: 24px;
}
.image03 {
  top: 150px;
  right: 0px;
  width: 650px;
  height: 900px;
  margin: auto;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.image04 {
  top: 0px;
  right: 0px;
  width: 100%;
  margin: auto;
  position: absolute;
  object-fit: cover;
}
.image05 {
  display: none;
}
.section01 {
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
}
.text05 {
  color: #ffffff;
  font-size: 40px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.features {
  width: 100%;
  display: flex;
  max-width: 1200px;
  margin-top: var(--dl-space-space-fiveunits);
  align-items: center;
  user-select: none;
  border-color: #5A5A5A;
  margin-bottom: 120px;
  flex-direction: row;
  justify-content: center;
  border-bottom-width: 1px;
}
.text06 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.text07 {
  color: rgb(121, 124, 128);
  font-family: Poppins;
}
.text08 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.text09 {
  color: rgb(121, 124, 128);
  font-family: Poppins;
}
.text10 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.text11 {
  color: rgb(121, 124, 128);
  font-family: Poppins;
}
.note {
  gap: 140px;
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.content1 {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  display: flex;
  max-width: 520px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.main1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.heading01 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
}
.paragraph {
  color: #CCCCCC;
  font-family: Poppins;
  line-height: 28px;
}
.explore-more {
  gap: var(--dl-space-space-oneandhalfunits);
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  border-color: #80FF44;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
  border-bottom-width: 1px;
}
.explore-more:hover {
  opacity: 0.5;
}
.text17 {
  color: #80FF44;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.image07 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: flex-end;
}
.image08 {
  object-fit: cover;
}
.section02 {
  gap: var(--dl-space-space-sixunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
}
.header01 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 900px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.text18 {
  color: rgb(255, 255, 255);
  font-size: 40px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.text19 {
  color: #C2C6CC;
  width: 100%;
  max-width: 600px;
  text-align: center;
  font-family: Poppins;
  line-height: 28px;
}
.note1 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.image09 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.image10 {
  object-fit: cover;
}
.content2 {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.main2 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.caption2 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.heading02 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.get-started2 {
  display: flex;
  background-color: #80FF44;
}
.text20 {
  color: #0C100C;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.note2 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row-reverse;
  justify-content: center;
}
.image11 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.image12 {
  object-fit: cover;
}
.content3 {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.main3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.caption3 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.section04 {
  color: rgb(198, 255, 75);
}
.heading04 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.header02 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.checkmarks {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.get-started3 {
  display: flex;
  background-color: #80FF44;
}
.text21 {
  color: #0C100C;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.section05 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  border-color: #51515A;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
  border-top-width: 1px;
}
.header03 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.left {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.right {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.paragraph3 {
  width: 100%;
  max-width: 480px;
}
.cards {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.section07 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
}
.note3 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row-reverse;
  justify-content: center;
}
.image13 {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.image14 {
  object-fit: cover;
}
.content4 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.caption4 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.heading07 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.header04 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.section09 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
}
.cube {
  top: 20px;
  left: 0px;
  width: 120px;
  height: 120px;
  display: flex;
  position: absolute;
  transform: rotateX(240deg) rotateY(25deg) rotateZ(-110deg);
  align-items: center;
  flex-direction: column;
  justify-content: center;
  transform-style: preserve-3d;
}
.top {
  transform: translateZ(-120px);
  background-image: linear-gradient(270deg, rgb(253, 253, 253) 0.00%,rgb(178, 178, 178) 100.00%);
}
.front {
  transform: rotateX(90deg);
  background: grey;
  background-image: linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%);
  transform-origin: bottom;
}
.left1 {
  width: 120px;
  transform: translateZ(-120px) rotateY(90deg);
  background-image: linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%);
  transform-origin: right;
}
.banner {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-fiveunits);
  z-index: 50;
  max-width: 1200px;
  align-items: center;
  border-radius: 20px;
  justify-content: space-between;
  background-color: #292929;
}
.header05 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.description {
  font-size: 20px;
  line-height: 30px;
}
.buttons1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  justify-content: center;
}
.get-started4 {
  display: flex;
  background-color: #80FF44;
}
.text25 {
  color: #0C100C;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
  white-space: nowrap;
}
.book-demo {
  display: flex;
  background-color: #ffffff;
}
.text26 {
  color: rgb(12, 16, 12);
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
  white-space: nowrap;
}
.section10 {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
}
.cube1 {
  right: -150px;
  width: 210px;
  bottom: -80px;
  height: 210px;
  margin: auto;
  display: flex;
  position: absolute;
  transform: rotateX(240deg) rotateY(50deg) rotateZ(-110deg);
  align-items: center;
  flex-direction: column;
  justify-content: center;
  transform-style: preserve-3d;
}
.top1 {
  transform: translateZ(-210px);
  background-image: linear-gradient(270deg, rgb(253, 253, 253) 0.00%,rgb(178, 178, 178) 100.00%);
}
.front1 {
  transform: rotateX(90deg);
  background: grey;
  background-image: linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%);
  transform-origin: bottom;
}
.left2 {
  width: 210px;
  transform: translateZ(-210px) rotateY(90deg);
  background-image: linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%);
  transform-origin: right;
}
.pricing {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  z-index: 50;
  max-width: 1200px;
  align-items: center;
  border-radius: 20px;
  flex-direction: column;
  justify-content: center;
}
.header06 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 900px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.left3 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.right1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.paragraph4 {
  width: 100%;
  font-size: 18px;
  max-width: 600px;
  text-align: center;
  line-height: 32px;
}
.plans-container {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.switch {
  gap: var(--dl-space-space-unit);
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: center;
  border-radius: 50px;
  flex-direction: row;
  justify-content: center;
  background-color: #292929;
}
.text27 {
  color: #ffffff;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.switch2 {
  padding-top: var(--dl-space-space-unit);
  background-color: #80FF44;
}
.text28 {
  color: rgb(0, 0, 0);
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.plans {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-halfunit);
  z-index: 50;
  max-width: 1200px;
  align-items: center;
  border-radius: 50px;
  flex-direction: row;
  justify-content: center;
}
.plan {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: flex-start;
  background-color: #292929;
}
.details {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.header07 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.name {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-family: Poppins;
  line-height: 36px;
}
.pricing1 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.price {
  color: #ffffff;
  font-size: 40px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.duration {
  color: #B3B3B3;
  font-size: 20px;
  font-family: Poppins;
  line-height: 40px;
}
.description1 {
  color: rgba(255, 255, 255, 0.8);
  font-family: Poppins;
  line-height: 22px;
}
.buy-details {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.buy {
  width: 100%;
  display: flex;
  background-color: #80FF44;
}
.text29 {
  color: rgb(12, 16, 12);
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.features1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.heading11 {
  color: rgb(255, 255, 255);
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 28px;
}
.list {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.plan1 {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: flex-start;
  background-color: #292929;
}
.details1 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.header08 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.name1 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-family: Poppins;
  line-height: 36px;
}
.pricing2 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.price1 {
  color: rgb(255, 255, 255);
  font-size: 40px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.duration1 {
  color: #B3B3B3;
  font-size: 20px;
  font-family: Poppins;
  line-height: 40px;
}
.description2 {
  color: rgba(255, 255, 255, 0.8);
  font-family: Poppins;
  line-height: 22px;
}
.buy-details1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.buy1 {
  width: 100%;
  display: flex;
  background-color: #80FF44;
}
.text32 {
  color: rgb(12, 16, 12);
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.features2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.heading12 {
  color: rgb(255, 255, 255);
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 28px;
}
.list1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.plan2 {
  gap: var(--dl-space-space-threeunits);
  flex: 1;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-twounits);
  border-radius: 20px;
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: flex-start;
  background-color: #292929;
}
.details2 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.header09 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.name2 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-family: Poppins;
  line-height: 36px;
}
.pricing3 {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.price2 {
  color: rgb(255, 255, 255);
  font-size: 40px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 600;
}
.duration2 {
  color: #B3B3B3;
  font-size: 20px;
  font-family: Poppins;
  line-height: 40px;
}
.description3 {
  color: rgba(255, 255, 255, 0.8);
  font-family: Poppins;
  line-height: 22px;
}
.buy-details2 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.buy2 {
  width: 100%;
  display: flex;
  background-color: #80FF44;
}
.text35 {
  color: rgb(12, 16, 12);
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.features3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.heading13 {
  color: rgb(255, 255, 255);
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 28px;
}
.list2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.help {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: flex-start;
}
.text38 {
  color: #ffffff;
  font-family: Poppins;
  line-height: 24px;
}
.contact-support {
  gap: var(--dl-space-space-oneandhalfunits);
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  border-color: #80FF44;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
  border-bottom-width: 1px;
}
.contact-support:hover {
  opacity: 0.5;
}
.text41 {
  color: rgb(128, 255, 68);
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.section12 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  border-color: #51515A;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
  border-top-width: 1px;
}
.header10 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.left4 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.heading14 {
  text-align: center;
}
.right2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.paragraph5 {
  width: 100%;
  max-width: 600px;
  text-align: center;
}
.cards1 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-threeunits);
  max-width: 1200px;
  align-items: flex-start;
  flex-direction: row;
  grid-template-columns: auto auto auto;
}
.container1 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  flex-direction: column;
}
.container2 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  flex-direction: column;
}
.container3 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  flex-direction: column;
}
.view-more {
  gap: var(--dl-space-space-oneandhalfunits);
  cursor: pointer;
  display: none;
  transition: 0.3s;
  align-items: center;
  border-color: #80FF44;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: center;
  border-bottom-width: 1px;
}
.view-more:hover {
  opacity: 0.5;
}
.text42 {
  color: rgb(128, 255, 68);
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.section14 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  border-color: #51515A;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
  border-top-width: 1px;
}
.header11 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.heading15 {
  text-align: center;
}
.cards2 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.section16 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  border-color: #51515A;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
  border-top-width: 1px;
}
.header12 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.heading16 {
  text-align: center;
}
.accordion {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.section18 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #292929;
}
.content5 {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 1200px;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.header13 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: flex-start;
}
.heading17 {
  text-align: left;
}
.buttons2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.i-o-s {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  flex-direction: row;
  background-color: #0F0F0F;
}
.icon {
  width: 16px;
  object-fit: cover;
}
.text43 {
  color: #ffffff;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.android {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  flex-direction: row;
  background-color: #0F0F0F;
}
.icon1 {
  width: 16px;
  object-fit: cover;
}
.text44 {
  color: rgb(255, 255, 255);
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.image15 {
  right: 0px;
  width: 470px;
  bottom: 0px;
  position: absolute;
  object-fit: cover;
}
.footer {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
  justify-content: center;
}
.content6 {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.main-content {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.content7 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: flex-start;
}
.main4 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.header14 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.branding {
  width: 120px;
  object-fit: cover;
}
.text45 {
  color: rgb(255, 255, 255);
  width: 100%;
  font-size: 14px;
  max-width: 260px;
  font-family: Poppins;
  line-height: 21px;
}
.socials {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: flex-start;
}
.link {
  display: contents;
}
.link1 {
  display: contents;
}
.link2 {
  display: contents;
}
.categories {
  gap: var(--dl-space-space-fourunits);
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.category {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.header15 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.links {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.category1 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 175px;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.header16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.links1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.copyright {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.text59 {
  color: #C4C4C4;
  width: 100%;
  font-size: 14px;
  font-family: Poppins;
  line-height: 21px;
}
.subscribe {
  gap: var(--dl-space-space-unit);
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.main5 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.heading18 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  max-width: 275px;
  font-style: normal;
  text-align: left;
  font-weight: 500;
  line-height: 30px;
}
.input-field {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding: var(--dl-space-space-halfunit);
  align-items: center;
  border-radius: 50px;
  flex-direction: row;
  justify-content: center;
  background-color: #292929;
}
.textinput {
  flex: 1;
  color: #ffffff;
  height: 24px;
  line-height: 24px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  outline-style: none;
  background-color: rgba(217, 217, 217, 0);
}
.buy3 {
  display: flex;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: #80FF44;
}
.text60 {
  color: rgb(12, 16, 12);
  display: none;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.text61 {
  color: rgb(12, 16, 12);
  display: flex;
  font-size: 16px;
  font-style: normal;
  font-family: Poppins;
  font-weight: 500;
  line-height: 24px;
}
.notice {
  color: #686868;
  font-size: 14px;
  max-width: 400px;
  font-style: normal;
  text-align: left;
  font-weight: 400;
  line-height: 21px;
}
.copyright1 {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  width: 100%;
  display: none;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.text64 {
  color: #C4C4C4;
  width: 100%;
  font-size: 14px;
  font-family: Poppins;
  line-height: 21px;
}
@media(max-width: 991px) {
  .section {
    height: auto;
    padding-left: 0px;
    padding-right: 0px;
  }
  .hero {
    gap: var(--dl-space-space-fourunits);
    flex: 1;
    position: relative;
    max-width: auto;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .content {
    position: relative;
    align-items: center;
  }
  .main {
    align-items: center;
  }
  .heading {
    text-align: left;
  }
  .caption {
    text-align: left;
  }
  .buttons {
    width: 100%;
  }
  .get-started {
    flex: 1;
  }
  .get-started1 {
    flex: 1;
  }
  .highlight {
    width: 100%;
    flex-direction: column;
  }
  .image03 {
    right: 0px;
    display: none;
    position: absolute;
    flex-direction: column;
  }
  .image05 {
    width: 100%;
    display: flex;
    align-items: flex-end;
    flex-direction: column;
  }
  .image06 {
    width: 600px;
  }
  .text05 {
    text-align: center;
  }
  .note {
    gap: var(--dl-space-space-fourunits);
    flex-direction: column;
  }
  .content1 {
    max-width: 100%;
  }
  .main1 {
    align-items: flex-start;
  }
  .text18 {
    text-align: center;
  }
  .section05 {
    gap: var(--dl-space-space-threeunits);
    padding-top: 100px;
    padding-bottom: 100px;
  }
  .header03 {
    gap: var(--dl-space-space-unit);
    align-items: flex-start;
    flex-direction: column;
    justify-content: flex-start;
  }
  .cards {
    gap: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
  }
  .section07 {
    padding-top: 0px;
  }
  .note3 {
    flex-direction: column-reverse;
  }
  .banner {
    gap: var(--dl-space-space-twounits);
    flex-direction: column;
    justify-content: center;
  }
  .buttons1 {
    width: 100%;
    flex-direction: column;
  }
  .get-started4 {
    width: 100%;
  }
  .book-demo {
    width: 100%;
  }
  .plans {
    flex-direction: column;
  }
  .section12 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .cards1 {
    grid-template-columns: auto;
  }
  .container3 {
    display: none;
  }
  .view-more {
    display: flex;
    border-color: #CCCCCC;
  }
  .text42 {
    color: #CCCCCC;
    font-style: normal;
    font-weight: 500;
    line-height: 24px;
  }
  .cards2 {
    gap: var(--dl-space-space-halfunit);
  }
  .content5 {
    align-items: center;
    flex-direction: column;
  }
  .buttons2 {
    width: 100%;
  }
  .i-o-s {
    flex: 1;
    justify-content: center;
  }
  .android {
    flex: 1;
    justify-content: center;
  }
  .image15 {
    position: static;
  }
  .content6 {
    gap: var(--dl-space-space-threeunits);
    align-items: flex-start;
    flex-direction: column;
    justify-content: flex-start;
  }
  .copyright {
    display: none;
  }
  .copyright1 {
    display: flex;
  }
}
@media(max-width: 767px) {
  .content {
    gap: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .heading {
    font-size: 40px;
  }
  .caption {
    color: rgb(255, 255, 255);
    font-size: 16px;
    font-family: Poppins;
    line-height: 24px;
  }
  .get-started {
    padding-top: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-unit);
  }
  .get-started1 {
    display: none;
  }
  .caption1 {
    font-size: 14px;
    line-height: 21px;
  }
  .image06 {
    width: 500px;
  }
  .section01 {
    padding-top: 100px;
    padding-bottom: 100px;
  }
  .text05 {
    font-size: 32px;
    text-align: center;
  }
  .features {
    gap: var(--dl-space-space-oneandhalfunits);
    margin-top: var(--dl-space-space-threeunits);
    border-color: #5A5A5A;
    margin-bottom: var(--dl-space-space-threeunits);
    flex-direction: column;
  }
  .feature {
    width: 100%;
    padding-bottom: var(--dl-space-space-unit);
  }
  .text06 {
    font-size: 20px;
  }
  .feature1 {
    width: 100%;
    border-color: #5A5A5A;
    padding-bottom: var(--dl-space-space-unit);
    border-bottom-width: 1px;
  }
  .text08 {
    font-size: 20px;
  }
  .feature2 {
    width: 100%;
    padding-bottom: var(--dl-space-space-unit);
  }
  .text10 {
    font-size: 20px;
  }
  .note {
    gap: var(--dl-space-space-threeunits);
  }
  .main1 {
    width: 100%;
    align-items: flex-start;
  }
  .heading01 {
    font-size: 28px;
  }
  .paragraph {
    line-height: 24px;
  }
  .section02 {
    gap: var(--dl-space-space-fourunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .text18 {
    font-size: 32px;
    text-align: center;
  }
  .note1 {
    flex-direction: column-reverse;
  }
  .note2 {
    flex-direction: column-reverse;
  }
  .left {
    gap: var(--dl-space-space-unit);
  }
  .content4 {
    width: 100%;
  }
  .banner {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .cube1 {
    right: -250px;
  }
  .plan {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .plan1 {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .plan2 {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .help {
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .section12 {
    padding-top: var(--dl-space-space-fourunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .cards2 {
    gap: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
  }
  .section18 {
    padding-top: var(--dl-space-space-fourunits);
  }
  .header13 {
    padding-bottom: var(--dl-space-space-fiveunits);
  }
  .buttons2 {
    flex-direction: column;
  }
  .i-o-s {
    flex: 0 0 auto;
    width: 100%;
  }
  .android {
    flex: 0 0 auto;
    width: 100%;
  }
  .content7 {
    gap: var(--dl-space-space-threeunits);
    flex-direction: column;
  }
  .main4 {
    gap: var(--dl-space-space-twounits);
  }
  .categories {
    gap: var(--dl-space-space-twounits);
    flex-direction: column;
  }
  .text61 {
    color: rgb(12, 16, 12);
    font-size: 16px;
    font-style: normal;
    font-family: Poppins;
    font-weight: 500;
    line-height: 24px;
  }
}
@media(max-width: 479px) {
  .header {
    align-items: flex-start;
  }
  .heading {
    max-width: 280px;
  }
  .image06 {
    width: 400px;
  }
  .image08 {
    width: 100%;
  }
  .pricing {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .heading10 {
    font-size: 32px;
    text-align: center;
  }
  .paragraph4 {
    font-size: 16px;
  }
  .image15 {
    width: 100%;
  }
  .textinput {
    flex: 1;
  }
  .text60 {
    color: rgb(12, 16, 12);
    display: flex;
    font-size: 24px;
    font-style: normal;
    font-family: Inter;
    font-weight: 700;
    line-height: 24px;
    white-space: nowrap;
  }
  .text61 {
    color: rgb(12, 16, 12);
    display: none;
    font-size: 24px;
    font-style: normal;
    font-family: Inter;
    font-weight: 700;
    line-height: 24px;
  }
}
