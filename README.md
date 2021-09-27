# Helpers
Methods for operating simple JavaScript logic

Example

function choice(arr){
  let randomIndex = Math.floor(Math.random() * arr.length);
  return arr[randomIndex];
}

// for React  export { choice }
