require.paths.push('spec');
var sys = require('sys');
var jasmine = require('jasmine');

desc('Run Jasmine specs.');
task('spec', [], function (params) {
  jasmine.executeSpecsInFolder(__dirname + "/spec", function(runner, log) {
    process.exit(runner.results().failedCount);
  }, false, true, "_spec.js$");
});

