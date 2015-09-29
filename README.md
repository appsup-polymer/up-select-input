# up-select-input

A polymer input element with Material Design styling for selecting a value from multiple options.

## Usage

     <template is="dom-bind">
       <up-select-input value="{{_value}}" label="Select an option">
         <option value="1">option 1</option>
         <option value="2">option 2</option>
       </up-select-input>

       <br/>
       <br/>

       <div>selected value = <span>{{_value}}</span></div>
     </template>

