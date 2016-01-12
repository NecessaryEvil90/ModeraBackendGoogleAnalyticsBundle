# ModeraBackendGoogleAnalyticsBundle

[![Build Status](https://travis-ci.org/modera/ModeraBackendGoogleAnalyticsBundle.svg?branch=master)](https://travis-ci.org/modera/ModeraBackendGoogleAnalyticsBundle)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/modera/ModeraBackendGoogleAnalyticsBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/modera/ModeraBackendGoogleAnalyticsBundle/?branch=master)
[![StyleCI](https://styleci.io/repos/49496662/shield)](https://styleci.io/repos/49496662)

Provides support for gathering 'pageview' analytics in backend using Google Analytics.

## Installation

Add a dependency to your composer.json by running:

    composer require modera/backend-google-analytics-bundle

You don't have to manually update your AppKernel class if you have `modera/module-bundle` bundle installed already, otherwise
you need to add this to your AppKernel:

    new \Modera\BackendGoogleAnalyticsBundle\ModeraBackendGoogleAnalyticsBundle(),

## Licensing

This bundle is under the MIT license. See the complete license in the bundle:
Resources/meta/LICENSE