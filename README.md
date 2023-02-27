# AWS SNS SMS Sender Plugin

[![Quality](https://img.shields.io/badge/quality-experiment-red)](https://curity.io/resources/code-examples/status/)
[![Availability](https://img.shields.io/badge/availability-source-blue)](https://curity.io/resources/code-examples/status/)

A custom SMS Sender plugin for the Curity Identity Server that uses AWS SNS to send SMS messages.

## Building the Plugin

You can build the plugin by issuing the command `mvn package`. This will produce a JAR file in the `target` directory,
which can be installed.

## Installing the Plugin

To install the plugin, copy the compiled JAR (and all of its dependencies) into the :file:`${IDSVR_HOME}/usr/share/plugins/${pluginGroup}`
on each node, including the admin node. For more information about installing plugins, refer to the `https://curity.io/docs/idsvr/latest/developer-guide/plugins/index.html#plugin-installation`.

## Required Dependencies

For a list of the dependencies and their versions, run `mvn dependency:list`. Ensure that all of these are installed in
the plugin group; otherwise, they will not be accessible to this plug-in and run-time errors will result.

## More Information

Please visit [curity.io](https://curity.io/) for more information about the Curity Identity Server.

Copyright (C) 2023 Curity AB.
