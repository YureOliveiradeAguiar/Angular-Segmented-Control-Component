<strong>Inputs/Outputs:</strong><br>
<segmented-control
    [options]="options"
    [value]="selectedOption"
    (valueChanged)="selectedOption = $event"
/>

<strong>Inputs/Outputs:</strong><br>
<ul>
  <li>
      options: SegmentedControlOption[]= [
      {label:"abracadabra", value: 69},
      {label:"simSalomão", value: 420},
      {label:"teste", value: 123}
    ];
  </li>
  <li> [value]="123" //the current value </li>
</ul>
