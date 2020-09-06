1. First Name, Last Name (real ones): **Evgeniy Tulya**
2. Contact Info (add several ways to contact you): *Mail*: **evg.tulya@gmail.com**, *Linkedin*: **https://www.linkedin.com/in/evgeniy-tulya/**, *Number*: **+375(29)818-03-23**
3. Summary (your goal, wishes, reveal what is important for you, what do you want and why.
Some kind of self-presentation. In case of lack of experience  Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace . Rather being a Junior means always
learning new things from everywhere etc.).: **Web-Developer for more than one year. I've experienced in writing SPA, testing and debugging**
4. Skills (e.g. programming languages, frameworks, methodologies, version control, tools etc.): *PL*: **JavaScript**, *JS-library*: **React**, *methodology*: **BEM**, *VC*: **Git**. *Others*: **Webpack**, **SASS/LESS**, **npm**.
5. Code examples (LATEST): 

```javascript
import { connect } from 'react-redux';
import { addMessageActionCreator, updateMessageTextActionCreator } from '../../../../redux/messages-reducer';

import Messages from '../component';

const mapStateToProps = (state) => ({
  dialogs: state.messagesPage.dialogs,
  messages: state.messagesPage.messages,
  messageText: state.messagesPage.messageText,
});

const mapDispatchToProps = (dispatch) => ({
  addMessage: () => {
    dispatch(addMessageActionCreator());
  },
  updateMessageText: (text) => {
    dispatch(updateMessageTextActionCreator(text));
  },
});

const MessagesContainer = connect(mapStateToProps, mapDispatchToProps)(Messages);

export default MessagesContainer;
```

6. Experience (for a Junior Dev it means all kinds of experience: coding tests, projects from courses,
freelance projects - wherever they had the opportunity to demonstrate skills they have.
Also it would be awesome if you add links to source code): **I participated in EPAM Systems's training project in React and also I've done some projects for me**.
7. Education (including courses, seminars, lectures, online learning): **HTMLAcademy**, **RSSchool**, **Linkedin Learning**.
8. English (elaborate on what kind of practice you had, if any, how long it lasted and so on): **I train my English on courses and also thanks to lessons on YouTube** *(Elementary)*.