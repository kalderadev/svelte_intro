<script>
  	import Line from "svelte-chartjs/src/Line.svelte"

	let chartValues = [5.3,3.8,0.6,3.9,6.6,9.6,10.9,19.8,18.9,19,14.1,10.9,5.2,3.7,3.3,5.3,5.3,10.5,11.9,16.8,17.7,19.9,14.8,10.2,6,3,0.6,1.8,4.6,6.1,10.7,19,18.3,16.4,15.2,9.6,4.7,2.6,2.6,4.4];
	let chartLabels = ["Nov '18","Dec '18","Jan '19","Feb '19","Mar '19","Apr '19","May '19","Jun '19","Jul '19","Aug '19","Sep '19","Oct '19","Nov '19","Dec '19","Jan '20","Feb '20","Mar '20","Apr '20","May '20","Jun '20","Jul '20","Aug '20","Sep '20","Oct '20","Nov '20","Dec '20","Jan '21","Feb '21","Mar '21","Apr '21","May '21","Jun '21","Jul '21","Aug '21","Sep '21","Oct '21","Nov '21","Dec '21","Jan '22","Feb '22"];
	
	let dataLine = {
    labels: chartLabels,
    datasets: [
      {
        label: "Temperature",
        fill: true,
        lineTension: 0.3,
        backgroundColor: "rgba(225, 204,230, .3)",
        borderColor: "rgb(205, 130, 158)",
        borderCapStyle: "butt",
        borderDash: [],
        borderDashOffset: 0.0,
        borderJoinStyle: "miter",
        pointBorderColor: "rgb(205, 130,1 58)",
        pointBackgroundColor: "rgb(255, 255, 255)",
        pointBorderWidth: 10,
        pointHoverRadius: 5,
        pointHoverBackgroundColor: "rgb(0, 0, 0)",
        pointHoverBorderColor: "rgba(220, 220, 220,1)",
        pointHoverBorderWidth: 2,
        pointRadius: 1,
        pointHitRadius: 10,
        data: chartValues
      }
    ]
  };

</script>

<Line data={dataLine} options={{ responsive: true }}/>