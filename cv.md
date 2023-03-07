# h1 Sveta Markova
## h2 Contacts
### h3 **Location** __The Republic of Sakha (Yakutia), Yakutsk__
### h3 **Phone number** __+77756291280__
### h3 **GitHub** __AminokaAminoka__
### h3 **Email** __sveta.9595@mail.ru__

## h2 About Me
__Hello, I am a diligent, responsible person, a bit of an introvert. Currently I work as a front-end developer in the Yakut startup (__[Boontar](https://boontar.ru/)__).I want to know more cool and interesting__

## h2 Skills
+__HTML&CSS__
+__JavaScript,JSON__
+__React JS / Native__
+__GitHub__
+__Figma__

## h2 Code Examples

examples = (inputDate) => {
    let todayDate = moment.utc();
    if(inputDate){
        let date = moment(new Date(inputDate));
        date.set({hour: 0, minute: 0, second: 0, millisecond: 0})
        today.set({hour: 0, minute: 0, second: 0, millisecond: 0})
        let dateMill = date.valueOf()
        let todayMill = today.valueOf();
        let range = (todayMill - dateMill) / 86400000;
        if (range < 1 || range == 0) {
            return 'Today'
        } else if (range < 2 || range == 1) {
            return 'Yesterday'
        } else if (range == -1) {
            return 'Tomorrow'
        } else {
            return date.format('DD-MM-YYYY')
        }
    } else return '-'
}

##  h2 Education
+__Northeastern federal university, bachelor physics__
+__Northeastern federal university, magistracy physics__

##  h2 Languages
+__Yakut - native speaker.__
+__Russian - second language__
+__French - A2__
+__English - A1?(now I'm learning)__