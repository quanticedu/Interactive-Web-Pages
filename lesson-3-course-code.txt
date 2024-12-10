function Course(name, time, building, room){
    this.name = name,
    this.time = time,
    this.building = building,
    this.room = room,
    this.getTime = function() {
        return this.name =  " at " + this.time
    },
    this.getLocation = function() {
        return this.building + ", " + this.room
    }
}

const course1 = new Course("ARTG 80", "8:00am", "Henry", 204)
const course2 = new Course("CSE 30", "9:45am", "Cowell", 210)
const course3 = new Course("CSE 111", "12:15pm", "Cowell", 120)
const course4 = new Course("MATH 19B", "2:00pm", "Kresge", 312)
const course5 = new Course("CMPM 170", "4:30pm", "Crown", 202)