/* 
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */


 angular.module('sampleNgView', ['ngRoute'])
                .config(function($routeProvider) {
                    
                    $routeProvider
            
                .when('/', {
                    templateUrl: 'pages/firstPage.html',
                    controller: 'firstPageController'
                    })
                
                .when('/pageTwo', {
                    templateUrl: 'pages/secondPage.html',
                    controller: 'secondPageController'
                    })
                
                    
                .when('/pageThree', {
                    templateUrl: 'pages/thirdPage.html',
                    controller: 'thirdPageController'
                    })
                    
                .otherwise({
                    redirectTo: '/'
                    });
        })
        
            .controller('firstPageController', ['$scope', function($scope) {
                    $scope.msg = "First Page";
        }])
            .controller('secondPageController', ['$scope', function($scope) {
                    $scope.msg = "Second Page";
        }])
    
            .controller('thirdPageController', ['$scope', function($scope) {
                    $scope.msg = "Third Page";
        }])
    ;
