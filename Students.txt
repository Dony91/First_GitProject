const students = [
  { name: "Asha", marks: 80 },
  { name: "Bala", marks: 60 },
  { name: "Chitra", marks: 90 }
];

const topStudents = students
  .filter(student => student.marks > 70) 
  .map(student => student.name); 
console.log(topStudents);
