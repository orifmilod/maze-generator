<h1>Perfect Maze Generator using Unity-3D and C#</h1>

This project is a simple Unity-3D project that generates a random perfect maze with given width and height data using "Recursive backtracker" algorithm each time.

<a target="__blank" href="https://youtu.be/E0HdUfJBuWI"> Watch a short clip of this project. </a>
<h3> How Recursive-backtracker Algorithm works? </h3>
  The depth-first search algorithm of maze generation is frequently implemented using backtracking:
<ol>
    <li> Make the initial cell the current cell and mark it as visited.</li>
    <li> While there are unvisited cells. </li>
      <ol>
      <li> If the current cell has any neighbours which have not been visited</li>
          <ol> 
              <li> Choose randomly one of the unvisited neighbours</li>
              <li> Push the current cell to the stack</li>
              <li>Remove the wall between the current cell and the chosen cell</li>
              <li> Make the chosen cell the current cell and mark it as visited</li>
          </ol>
          <li>Else if stack is not empty</li>
            <ol> 
              <li>Pop a cell from the stack</li>
              <li>Make it the current cell</li>
            </ol>
</ol>
<br/>
   
 <a target="__blank" href="https://en.wikipedia.org/wiki/Maze_generation_algorithm"> Read more about maze generation algorithms. </a>
