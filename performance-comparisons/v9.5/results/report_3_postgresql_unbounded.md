### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 8ms | 4ms | 97.24
| UserStore.GetMany | avg | 3ms | 6ms | 3ms | 94.91
| ProductNoticesStore.GetViews | avg | 4ms | 6ms | 2ms | 52.33
| JobStore.Save | avg | 5ms | 7ms | 2ms | 36.40
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 245ms | 2.08s | 1.835s | 749.07
| UserStore.GetMany | p99 | 23ms | 89ms | 66ms | 282.65
| StatusStore.UpdateExpiredDNDStatuses | p99 | 94ms | 215ms | 121ms | 128.38
| JobStore.Save | p99 | 42ms | 85ms | 43ms | 101.18
| PostPersistentNotificationStore.Get | p99 | 23ms | 40ms | 17ms | 73.59
| PluginStore.List | p99 | 45ms | 73ms | 28ms | 61.77
| RoleStore.ChannelHigherScopedPermissions | p99 | 30ms | 40ms | 10ms | 33.06
| JobStore.GetCountByStatusAndType | p99 | 106ms | 119ms | 13ms | 12.26
| JobStore.GetAllByTypePage | p99 | 44ms | 47ms | 3ms | 6.74
| ChannelStore.GetMembersForUserWithPagination | p99 | 88ms | 92ms | 4ms | 4.55
| UserStore.GetByUsername | p99 | 47ms | 49ms | 2ms | 4.22
| ChannelStore.GetSidebarCategory | p99 | 201ms | 205ms | 4ms | 1.99
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 17ms | 0s | -17ms | -102.33
| ChannelStore.Update | avg | 19ms | 0s | -19ms | -102.02
| SessionStore.AnalyticsSessionCount | avg | 81ms | 0s | -81ms | -100.46
| CommandStore.AnalyticsCommandCount | avg | 63ms | 0s | -63ms | -100.32
| WebhookStore.AnalyticsOutgoingCount | avg | 58ms | 0s | -58ms | -99.74
| WebhookStore.AnalyticsIncomingCount | avg | 58ms | 0s | -58ms | -99.70
| DraftStore.Get | avg | 11ms | 0s | -11ms | -95.79
| ChannelStore.GetMemberOnly | avg | 5ms | 0s | -5ms | -92.12
| RetentionPolicyStore.GetCount | avg | 7ms | 1ms | -6ms | -91.71
| SystemStore.Save | avg | 2ms | 0s | -2ms | -91.14
| TokenStore.Cleanup | avg | 9ms | 1ms | -8ms | -86.32
| ChannelStore.GetMembers | avg | 17ms | 2ms | -15ms | -86.07
| UserStore.AnalyticsGetInactiveUsersCount | avg | 4ms | 1ms | -3ms | -83.40
| CommandWebhookStore.Cleanup | avg | 6ms | 1ms | -5ms | -79.29
| ChannelStore.CreateSidebarCategory | avg | 76ms | 18ms | -58ms | -76.18
| LicenseStore.GetAll | avg | 5ms | 1ms | -4ms | -75.33
| SessionStore.Remove | avg | 8ms | 3ms | -5ms | -66.39
| SchemeStore.GetAllPage | avg | 9ms | 3ms | -6ms | -64.81
| JobStore.UpdateStatusOptimistically | avg | 14ms | 5ms | -9ms | -62.90
| StatusStore.UpdateExpiredDNDStatuses | avg | 15ms | 6ms | -9ms | -61.67
| PreferenceStore.DeleteCategoryAndName | avg | 17ms | 7ms | -10ms | -58.19
| PostStore.SetPostReminder | avg | 12ms | 5ms | -7ms | -58.12
| SessionStore.GetSessionsExpired | avg | 12ms | 5ms | -7ms | -57.23
| SystemStore.GetByName | avg | 4ms | 2ms | -2ms | -55.09
| UserStore.Count | avg | 41ms | 19ms | -22ms | -54.07
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 6ms | 3ms | -3ms | -54.06
| ThreadStore.GetThreadFollowers | avg | 6ms | 3ms | -3ms | -52.33
| PostStore.GetSingle | avg | 6ms | 3ms | -3ms | -51.75
| ReactionStore.GetUniqueCountForPost | avg | 6ms | 3ms | -3ms | -50.96
| BotStore.Get | avg | 8ms | 4ms | -4ms | -50.52
| TeamStore.GetByName | avg | 4ms | 2ms | -2ms | -49.58
| JobStore.UpdateStatus | avg | 6ms | 3ms | -3ms | -48.57
| PostStore.AnalyticsPostCount | avg | 481ms | 248ms | -233ms | -48.48
| ThreadStore.MarkAllAsReadByChannels | avg | 6ms | 3ms | -3ms | -47.94
| ChannelStore.UpdateSidebarChannelsByPreferences | avg | 4ms | 2ms | -2ms | -47.93
| PostStore.GetPostReminderMetadata | avg | 8ms | 4ms | -4ms | -47.52
| PostPriorityStore.GetForPosts | avg | 9ms | 5ms | -4ms | -46.94
| FileInfoStore.Search | avg | 11ms | 6ms | -5ms | -46.86
| GroupStore.GetGroups | avg | 7ms | 4ms | -3ms | -46.04
| JobStore.GetAllByTypePage | avg | 7ms | 4ms | -3ms | -45.96
| ChannelStore.Save | avg | 29ms | 16ms | -13ms | -45.41
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 7ms | 4ms | -3ms | -44.95
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 7ms | 4ms | -3ms | -44.63
| ChannelStore.UpdateSidebarCategories | avg | 87ms | 48ms | -39ms | -44.61
| PostAcknowledgementStore.GetForPost | avg | 5ms | 3ms | -2ms | -43.61
| FileInfoStore.GetForPost | avg | 7ms | 4ms | -3ms | -43.50
| TeamStore.AnalyticsTeamCount | avg | 7ms | 4ms | -3ms | -42.98
| UserTermsOfServiceStore.GetByUser | avg | 5ms | 3ms | -2ms | -42.90
| DraftStore.GetDraftsForUser | avg | 5ms | 3ms | -2ms | -42.48
| LinkMetadataStore.Save | avg | 7ms | 4ms | -3ms | -42.23
| ChannelStore.GetPinnedPostCount | avg | 7ms | 4ms | -3ms | -41.71
| ThreadStore.Get | avg | 7ms | 4ms | -3ms | -41.62
| UserStore.Get | avg | 5ms | 3ms | -2ms | -40.76
| ReactionStore.ExistsOnPost | avg | 7ms | 4ms | -3ms | -40.58
| FileInfoStore.Get | avg | 7ms | 4ms | -3ms | -40.55
| ChannelStore.IncrementMentionCount | avg | 5ms | 3ms | -2ms | -40.25
| ChannelStore.GetMember | avg | 8ms | 5ms | -3ms | -39.78
| UserStore.GetProfileByIds | avg | 8ms | 5ms | -3ms | -39.54
| PreferenceStore.Get | avg | 8ms | 5ms | -3ms | -38.93
| PostStore.GetPostIdBeforeTime | avg | 5ms | 3ms | -2ms | -38.74
| FileInfoStore.Save | avg | 10ms | 6ms | -4ms | -38.72
| ChannelStore.AnalyticsTypeCount | avg | 23ms | 14ms | -9ms | -38.61
| ChannelStore.Get | avg | 8ms | 5ms | -3ms | -38.47
| TeamStore.GetAllPage | avg | 5ms | 3ms | -2ms | -38.38
| TeamStore.Get | avg | 5ms | 3ms | -2ms | -38.23
| PostAcknowledgementStore.GetForPosts | avg | 8ms | 5ms | -3ms | -38.09
| PostStore.GetEtag | avg | 8ms | 5ms | -3ms | -37.54
| JobStore.Get | avg | 11ms | 7ms | -4ms | -37.26
| PostPriorityStore.GetForPost | avg | 5ms | 3ms | -2ms | -37.23
| ChannelStore.GetFileCount | avg | 8ms | 5ms | -3ms | -36.62
| PostPersistentNotificationStore.GetSingle | avg | 5ms | 3ms | -2ms | -36.62
| ChannelStore.GetChannelUnread | avg | 8ms | 5ms | -3ms | -36.51
| ChannelStore.GetChannels | avg | 8ms | 5ms | -3ms | -36.12
| ReactionStore.Save | avg | 20ms | 13ms | -7ms | -35.65
| ThreadStore.MaintainMembership | avg | 11ms | 7ms | -4ms | -35.63
| UserStore.GetProfilesByUsernames | avg | 8ms | 5ms | -3ms | -35.53
| RetentionPolicyStore.GetAll | avg | 8ms | 5ms | -3ms | -35.44
| UserStore.Update | avg | 20ms | 13ms | -7ms | -34.99
| FileInfoStore.AttachToPost | avg | 12ms | 8ms | -4ms | -34.38
| TeamStore.GetTeamsForUser | avg | 6ms | 4ms | -2ms | -34.19
| ThreadStore.UpdateMembership | avg | 6ms | 4ms | -2ms | -33.90
| StatusStore.UpdateLastActivityAt | avg | 6ms | 4ms | -2ms | -33.73
| PostStore.GetPostsAfter | avg | 9ms | 6ms | -3ms | -33.53
| ThreadStore.GetTeamsUnreadForUser | avg | 9ms | 6ms | -3ms | -32.84
| StatusStore.SaveOrUpdate | avg | 91ms | 61ms | -30ms | -32.83
| PostStore.Get | avg | 15ms | 10ms | -5ms | -32.76
| LinkMetadataStore.Get | avg | 6ms | 4ms | -2ms | -32.70
| ReactionStore.GetForPost | avg | 6ms | 4ms | -2ms | -32.58
| ThreadStore.GetMembershipForUser | avg | 6ms | 4ms | -2ms | -32.26
| ChannelStore.CreateDirectChannel | avg | 47ms | 32ms | -15ms | -32.17
| ChannelStore.GetChannelsByUser | avg | 9ms | 6ms | -3ms | -32.12
| ThreadStore.GetTotalThreads | avg | 6ms | 4ms | -2ms | -32.09
| JobStore.GetAllByStatus | avg | 9ms | 6ms | -3ms | -32.06
| ThreadStore.MarkAsRead | avg | 6ms | 4ms | -2ms | -31.88
| ChannelStore.GetMembersForUser | avg | 9ms | 6ms | -3ms | -31.84
| TeamStore.GetChannelUnreadsForAllTeams | avg | 6ms | 4ms | -2ms | -31.83
| ThreadStore.GetTotalUnreadThreads | avg | 6ms | 4ms | -2ms | -31.73
| ThreadStore.GetTotalUnreadMentions | avg | 6ms | 4ms | -2ms | -31.62
| ThreadStore.GetThreadForUser | avg | 13ms | 9ms | -4ms | -31.38
| UserStore.GetUnreadCount | avg | 6ms | 4ms | -2ms | -30.88
| JobStore.GetCountByStatusAndType | avg | 7ms | 5ms | -2ms | -30.76
| ChannelStore.GetByName | avg | 7ms | 5ms | -2ms | -30.34
| PostStore.GetPosts | avg | 7ms | 5ms | -2ms | -30.15
| PostStore.GetPostsBefore | avg | 10ms | 7ms | -3ms | -29.98
| ThreadStore.GetThreadUnreadReplyCount | avg | 13ms | 9ms | -4ms | -29.98
| StatusStore.GetByIds | avg | 10ms | 7ms | -3ms | -29.88
| SessionStore.UpdateLastActivityAt | avg | 7ms | 5ms | -2ms | -29.78
| UserStore.AnalyticsActiveCount | avg | 45ms | 32ms | -13ms | -28.71
| ThreadStore.GetThreadsForUser | avg | 10ms | 7ms | -3ms | -28.61
| PostStore.Save | avg | 21ms | 15ms | -6ms | -28.56
| PostStore.GetPostsSince | avg | 25ms | 18ms | -7ms | -28.52
| ChannelStore.GetGuestCount | avg | 7ms | 5ms | -2ms | -28.47
| SessionStore.Save | avg | 11ms | 8ms | -3ms | -28.39
| PreferenceStore.Save | avg | 14ms | 10ms | -4ms | -28.24
| SessionStore.Get | avg | 11ms | 8ms | -3ms | -28.02
| ChannelStore.GetMemberForPost | avg | 11ms | 8ms | -3ms | -27.95
| ChannelStore.UpdateLastViewedAt | avg | 7ms | 5ms | -2ms | -27.59
| ChannelStore.SearchGroupChannels | avg | 11ms | 8ms | -3ms | -27.09
| PluginStore.SetWithOptions | avg | 8ms | 6ms | -2ms | -26.59
| PostStore.GetPostsByThread | avg | 11ms | 8ms | -3ms | -26.39
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 29ms | 22ms | -7ms | -24.23
| JobStore.UpdateOptimistically | avg | 9ms | 7ms | -2ms | -23.50
| PostStore.GetPostReminders | avg | 9ms | 7ms | -2ms | -22.33
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 137ms | 107ms | -30ms | -21.86
| WebhookStore.GetOutgoingByTeam | avg | 9ms | 7ms | -2ms | -21.67
| ProductNoticesStore.View | avg | 49ms | 39ms | -10ms | -20.27
| FileInfoStore.SetContent | avg | 15ms | 12ms | -3ms | -20.23
| ChannelStore.GetTeamChannels | avg | 35ms | 28ms | -7ms | -19.90
| ChannelStore.SaveMember | avg | 46ms | 37ms | -9ms | -19.71
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 41ms | 33ms | -8ms | -19.51
| ChannelStore.CreateInitialSidebarCategories | avg | 27ms | 22ms | -5ms | -18.30
| ChannelStore.GetMemberCount | avg | 34ms | 28ms | -6ms | -17.59
| UserStore.AutocompleteUsersInChannel | avg | 82ms | 68ms | -14ms | -17.01
| ComplianceStore.MessageExport | avg | 12ms | 10ms | -2ms | -16.82
| PostStore.Delete | avg | 19ms | 16ms | -3ms | -15.65
| UserStore.GetAllProfilesInChannel | avg | 403ms | 343ms | -60ms | -14.87
| UserStore.Search | avg | 56ms | 48ms | -8ms | -14.20
| ChannelStore.GetPublicChannelsForTeam | avg | 30ms | 26ms | -4ms | -13.19
| ChannelStore.Autocomplete | avg | 64ms | 57ms | -7ms | -10.89
| PostStore.SearchPostsForUser | avg | 270ms | 244ms | -26ms | -9.61
| TeamStore.SaveMember | avg | 35ms | 32ms | -3ms | -8.53
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 24ms | 22ms | -2ms | -8.47
| UserStore.Save | avg | 79ms | 75ms | -4ms | -5.07
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.Update | p99 | 25ms | 0s | -25ms | -100.60
| DraftStore.Get | p99 | 49ms | 0s | -49ms | -100.51
| WebhookStore.AnalyticsIncomingCount | p99 | 100ms | 0s | -100ms | -100.50
| CommandStore.AnalyticsCommandCount | p99 | 100ms | 0s | -100ms | -100.50
| WebhookStore.AnalyticsOutgoingCount | p99 | 100ms | 0s | -100ms | -100.50
| SessionStore.AnalyticsSessionCount | p99 | 100ms | 0s | -100ms | -100.50
| ChannelStore.GetMemberOnly | p99 | 71ms | 0s | -71ms | -100.07
| ChannelStore.GetMemberCountsByGroup | p99 | 96ms | 0s | -96ms | -100.00
| ChannelStore.CreateSidebarCategory | p99 | 478ms | 25ms | -453ms | -94.87
| ChannelStore.GetMembers | p99 | 97ms | 5ms | -92ms | -94.85
| JobStore.UpdateStatusOptimistically | p99 | 345ms | 34ms | -311ms | -90.14
| TokenStore.Cleanup | p99 | 25ms | 5ms | -20ms | -80.97
| PreferenceStore.DeleteCategoryAndName | p99 | 225ms | 45ms | -180ms | -80.18
| RetentionPolicyStore.GetCount | p99 | 24ms | 5ms | -19ms | -77.87
| CommandWebhookStore.Cleanup | p99 | 24ms | 5ms | -19ms | -77.87
| SessionStore.Remove | p99 | 92ms | 21ms | -71ms | -77.17
| PostStore.SetPostReminder | p99 | 94ms | 23ms | -71ms | -75.33
| ChannelStore.Save | p99 | 355ms | 99ms | -256ms | -72.12
| PostStore.GetPostReminderMetadata | p99 | 77ms | 23ms | -54ms | -70.13
| RetentionPolicyStore.GetAll | p99 | 25ms | 10ms | -15ms | -61.10
| FileInfoStore.Search | p99 | 25ms | 10ms | -15ms | -60.36
| UserStore.Update | p99 | 244ms | 99ms | -145ms | -59.50
| LicenseStore.GetAll | p99 | 24ms | 10ms | -14ms | -57.71
| ChannelStore.GetTeamChannels | p99 | 231ms | 98ms | -133ms | -57.70
| LinkMetadataStore.Save | p99 | 82ms | 38ms | -44ms | -53.43
| ChannelStore.UpdateSidebarCategories | p99 | 474ms | 225ms | -249ms | -52.56
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 10ms | 5ms | -5ms | -51.09
| SchemeStore.GetAllPage | p99 | 10ms | 5ms | -5ms | -50.25
| PostStore.AnalyticsPostCount | p99 | 990ms | 495ms | -495ms | -50.00
| JobStore.UpdateStatus | p99 | 69ms | 35ms | -34ms | -48.92
| PostStore.Get | p99 | 178ms | 97ms | -81ms | -45.42
| ThreadStore.Get | p99 | 85ms | 47ms | -38ms | -44.64
| FileInfoStore.GetForPost | p99 | 81ms | 45ms | -36ms | -44.33
| ChannelStore.GetChannelsByUser | p99 | 88ms | 49ms | -39ms | -44.26
| ThreadStore.MarkAllAsReadByChannels | p99 | 82ms | 46ms | -36ms | -43.91
| TeamStore.GetByName | p99 | 53ms | 30ms | -23ms | -43.08
| ReactionStore.ExistsOnPost | p99 | 79ms | 45ms | -34ms | -43.07
| PostStore.GetPostsAfter | p99 | 78ms | 45ms | -33ms | -42.53
| ThreadStore.MaintainMembership | p99 | 149ms | 86ms | -63ms | -42.25
| ReactionStore.GetUniqueCountForPost | p99 | 76ms | 44ms | -32ms | -42.03
| ChannelStore.Get | p99 | 83ms | 49ms | -34ms | -41.11
| PostStore.GetPostsByThread | p99 | 83ms | 49ms | -34ms | -40.96
| PluginStore.Delete | p99 | 42ms | 25ms | -17ms | -40.24
| PostStore.Update | p99 | 193ms | 116ms | -77ms | -39.96
| PostAcknowledgementStore.GetForPosts | p99 | 93ms | 56ms | -37ms | -39.86
| ChannelStore.GetChannelUnread | p99 | 83ms | 50ms | -33ms | -39.68
| ChannelStore.GetMemberForPost | p99 | 82ms | 51ms | -31ms | -37.78
| ThreadStore.GetTotalUnreadMentions | p99 | 72ms | 45ms | -27ms | -37.68
| PostStore.GetPostsSince | p99 | 200ms | 125ms | -75ms | -37.59
| ThreadStore.GetMembershipForUser | p99 | 74ms | 46ms | -28ms | -37.58
| ThreadStore.GetTotalThreads | p99 | 72ms | 45ms | -27ms | -37.55
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 77ms | 48ms | -29ms | -37.50
| ChannelStore.CreateDirectChannel | p99 | 388ms | 244ms | -144ms | -37.12
| ReactionStore.GetForPost | p99 | 68ms | 43ms | -25ms | -36.87
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 74ms | 47ms | -27ms | -36.44
| PostStore.GetPostIdBeforeTime | p99 | 71ms | 45ms | -26ms | -36.39
| ThreadStore.GetTotalUnreadThreads | p99 | 72ms | 46ms | -26ms | -36.14
| ThreadStore.MarkAsRead | p99 | 61ms | 39ms | -22ms | -36.10
| UserStore.Get | p99 | 67ms | 43ms | -24ms | -36.03
| LinkMetadataStore.Get | p99 | 70ms | 45ms | -25ms | -35.96
| TeamStore.GetTeamsForUser | p99 | 73ms | 47ms | -26ms | -35.86
| PreferenceStore.GetAll | p99 | 81ms | 52ms | -29ms | -35.73
| PreferenceStore.Save | p99 | 191ms | 123ms | -68ms | -35.61
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 73ms | 47ms | -26ms | -35.54
| ChannelStore.UpdateLastViewedAt | p99 | 70ms | 45ms | -25ms | -35.50
| TeamStore.GetAllPage | p99 | 73ms | 47ms | -26ms | -35.39
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 63ms | 41ms | -22ms | -34.71
| ChannelStore.GetPinnedPostCount | p99 | 84ms | 55ms | -29ms | -34.67
| SessionStore.Get | p99 | 142ms | 93ms | -49ms | -34.49
| UserStore.GetUnreadCount | p99 | 69ms | 46ms | -23ms | -33.55
| FileInfoStore.Save | p99 | 93ms | 62ms | -31ms | -33.17
| UserStore.GetAllProfilesInChannel | p99 | 2.086s | 1.396s | -690ms | -33.08
| ChannelStore.IncrementMentionCount | p99 | 70ms | 47ms | -23ms | -33.06
| PostStore.GetSingle | p99 | 64ms | 43ms | -21ms | -32.89
| TeamStore.GetMember | p99 | 28ms | 19ms | -9ms | -32.72
| TeamStore.GetTeamsByUserId | p99 | 68ms | 46ms | -22ms | -32.35
| PluginStore.SetWithOptions | p99 | 87ms | 59ms | -28ms | -32.28
| ChannelStore.GetGuestCount | p99 | 81ms | 55ms | -26ms | -32.04
| ChannelStore.SaveMember | p99 | 358ms | 244ms | -114ms | -31.88
| PostPriorityStore.GetForPosts | p99 | 94ms | 64ms | -30ms | -31.76
| ChannelStore.GetFileCount | p99 | 79ms | 54ms | -25ms | -31.60
| ReactionStore.Save | p99 | 215ms | 147ms | -68ms | -31.58
| FileInfoStore.Get | p99 | 86ms | 59ms | -27ms | -31.40
| SessionStore.UpdateLastActivityAt | p99 | 61ms | 42ms | -19ms | -31.07
| ChannelStore.GetMember | p99 | 91ms | 63ms | -28ms | -30.88
| UserStore.UpdateFailedPasswordAttempts | p99 | 68ms | 47ms | -21ms | -30.71
| UserStore.GetProfilesByUsernames | p99 | 89ms | 62ms | -27ms | -30.49
| AuditStore.Save | p99 | 66ms | 46ms | -20ms | -30.46
| GroupStore.GetGroups | p99 | 66ms | 46ms | -20ms | -30.12
| PreferenceStore.Get | p99 | 86ms | 60ms | -26ms | -30.07
| TeamStore.Get | p99 | 58ms | 41ms | -17ms | -29.44
| ThreadStore.GetTeamsUnreadForUser | p99 | 92ms | 65ms | -27ms | -29.41
| UserStore.GetForLogin | p99 | 65ms | 46ms | -19ms | -29.11
| StatusStore.UpdateLastActivityAt | p99 | 59ms | 42ms | -17ms | -28.95
| UserTermsOfServiceStore.GetByUser | p99 | 62ms | 44ms | -18ms | -28.93
| UserStore.GetProfileByIds | p99 | 87ms | 62ms | -25ms | -28.70
| ThreadStore.GetThreadForUser | p99 | 119ms | 86ms | -33ms | -27.72
| ChannelStore.GetChannels | p99 | 87ms | 63ms | -24ms | -27.59
| ThreadStore.UpdateMembership | p99 | 55ms | 40ms | -15ms | -27.39
| JobStore.UpdateOptimistically | p99 | 90ms | 66ms | -24ms | -26.69
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 49ms | 36ms | -13ms | -26.68
| ThreadStore.GetThreadsForUser | p99 | 91ms | 67ms | -24ms | -26.47
| ChannelStore.GetMembersForUser | p99 | 87ms | 64ms | -23ms | -26.43
| PostPersistentNotificationStore.GetSingle | p99 | 53ms | 39ms | -14ms | -26.20
| PostStore.GetPosts | p99 | 61ms | 45ms | -16ms | -26.07
| PostAcknowledgementStore.GetForPost | p99 | 54ms | 40ms | -14ms | -25.75
| ChannelStore.GetByName | p99 | 67ms | 50ms | -17ms | -25.53
| PostStore.GetPostsBefore | p99 | 90ms | 67ms | -23ms | -25.44
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 48ms | 36ms | -12ms | -25.10
| PostStore.Save | p99 | 227ms | 172ms | -55ms | -24.26
| StatusStore.GetByIds | p99 | 91ms | 69ms | -22ms | -24.20
| FileInfoStore.AttachToPost | p99 | 106ms | 81ms | -25ms | -23.66
| GroupStore.GetByName | p99 | 61ms | 47ms | -14ms | -22.94
| PostStore.GetPostIdAfterTime | p99 | 52ms | 40ms | -12ms | -22.89
| SystemStore.GetByName | p99 | 53ms | 41ms | -12ms | -22.80
| ThreadStore.GetThreadUnreadReplyCount | p99 | 92ms | 71ms | -21ms | -22.73
| SessionStore.Save | p99 | 97ms | 75ms | -22ms | -22.65
| UserStore.IsEmpty | p99 | 31ms | 24ms | -7ms | -22.56
| PostStore.GetEtag | p99 | 89ms | 69ms | -20ms | -22.52
| ThreadStore.GetThreadFollowers | p99 | 55ms | 43ms | -12ms | -21.64
| ChannelStore.GetMemberCount | p99 | 212ms | 169ms | -43ms | -20.25
| FileInfoStore.SetContent | p99 | 153ms | 122ms | -31ms | -20.22
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 220ms | 177ms | -43ms | -19.51
| ProductNoticesStore.View | p99 | 463ms | 374ms | -89ms | -19.23
| UserStore.GetAllProfiles | p99 | 47ms | 38ms | -9ms | -19.01
| UserStore.UpdateLastLogin | p99 | 48ms | 39ms | -9ms | -18.93
| WebhookStore.GetOutgoingByTeam | p99 | 90ms | 73ms | -17ms | -18.85
| PostPriorityStore.GetForPost | p99 | 49ms | 40ms | -9ms | -18.50
| ChannelStore.GetAllChannelMembersForUser | p99 | 23ms | 19ms | -4ms | -17.34
| ChannelStore.SearchGroupChannels | p99 | 94ms | 78ms | -16ms | -17.09
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 236ms | 197ms | -39ms | -16.53
| JobStore.GetAllByStatus | p99 | 98ms | 82ms | -16ms | -16.37
| UserStore.UpdateUpdateAt | p99 | 47ms | 40ms | -7ms | -14.82
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 481ms | 418ms | -63ms | -13.10
| StatusStore.Get | p99 | 49ms | 43ms | -6ms | -12.32
| PluginStore.Get | p99 | 41ms | 36ms | -5ms | -12.27
| UserStore.Count | p99 | 98ms | 87ms | -11ms | -11.17
| UserStore.AutocompleteUsersInChannel | p99 | 415ms | 370ms | -45ms | -10.84
| PostStore.GetPostReminders | p99 | 49ms | 44ms | -5ms | -10.30
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 49ms | 44ms | -5ms | -10.22
| ChannelStore.CreateInitialSidebarCategories | p99 | 253ms | 228ms | -25ms | -9.89
| TeamStore.SaveMember | p99 | 221ms | 200ms | -21ms | -9.50
| PostPersistentNotificationStore.DeleteExpired | p99 | 24ms | 22ms | -2ms | -8.48
| BotStore.Get | p99 | 48ms | 44ms | -4ms | -8.35
| StatusStore.SaveOrUpdate | p99 | 981ms | 900ms | -81ms | -8.26
| JobStore.Get | p99 | 94ms | 88ms | -6ms | -6.37
| ChannelStore.AnalyticsTypeCount | p99 | 50ms | 47ms | -3ms | -6.06
| ComplianceStore.MessageExport | p99 | 100ms | 94ms | -6ms | -6.00
| UserStore.Search | p99 | 241ms | 227ms | -14ms | -5.82
| ChannelStore.GetPublicChannelsForTeam | p99 | 176ms | 168ms | -8ms | -4.54
| UserStore.Save | p99 | 247ms | 237ms | -10ms | -4.06
| UserStore.AnalyticsActiveCount | p99 | 99ms | 96ms | -3ms | -3.04
| PostStore.Delete | p99 | 92ms | 90ms | -2ms | -2.19
| PostStore.SearchPostsForUser | p99 | 2.497s | 2.457s | -40ms | -1.60
| ChannelStore.Autocomplete | p99 | 247ms | 244ms | -3ms | -1.22
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroups | avg | 2ms | 5ms | 3ms | 143.81
| updateReadStateAllThreadsByUser | avg | 4ms | 9ms | 5ms | 118.86
| patchPost | avg | 94ms | 147ms | 53ms | 56.62
| getUsers | avg | 57ms | 70ms | 13ms | 22.62
| followThreadByUser | avg | 30ms | 36ms | 6ms | 20.20
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 245ms | 2.08s | 1.835s | 748.77
| patchPost | p99 | 475ms | 2.849s | 2.374s | 499.78
| getGroups | p99 | 5ms | 24ms | 19ms | 383.84
| followThreadByUser | p99 | 97ms | 223ms | 126ms | 129.56
| deletePost | p99 | 97ms | 221ms | 124ms | 127.62
| getUsers | p99 | 708ms | 875ms | 167ms | 23.60
| getJobsByType | p99 | 45ms | 47ms | 2ms | 4.47
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 18ms | 0s | -18ms | -102.41
| handleCheckCWSConnection | avg | 93ms | 0s | -93ms | -100.46
| updateCategoryForTeamForUser | avg | 200ms | 0s | -200ms | -100.08
| deleteDraft | avg | 10ms | 0s | -10ms | -97.81
| updateViewedProductNotices | avg | 7ms | 0s | -7ms | -94.99
| getProductNotices | avg | 7ms | 0s | -7ms | -94.31
| getChannelMembers | avg | 18ms | 3ms | -15ms | -82.68
| createCategoryForTeamForUser | avg | 116ms | 24ms | -92ms | -79.51
| getAnalytics | avg | 97ms | 32ms | -65ms | -67.19
| getPrevTrialLicense | avg | 5ms | 2ms | -3ms | -58.76
| searchFiles | avg | 16ms | 8ms | -8ms | -51.50
| getFilteredUsersStats | avg | 36ms | 19ms | -17ms | -47.31
| getUsersByNames | avg | 9ms | 5ms | -4ms | -45.43
| logout | avg | 138ms | 79ms | -59ms | -42.69
| setPostReminder | avg | 41ms | 24ms | -17ms | -41.93
| getChannelUnread | avg | 10ms | 6ms | -4ms | -41.36
| saveReaction | avg | 62ms | 38ms | -24ms | -38.97
| getChannelsForUser | avg | 11ms | 7ms | -4ms | -37.78
| getPostsForChannel | avg | 71ms | 44ms | -27ms | -37.77
| viewChannel | avg | 32ms | 20ms | -12ms | -37.73
| getThreadsForUser | avg | 11ms | 7ms | -4ms | -36.84
| getPostThread | avg | 38ms | 24ms | -14ms | -36.65
| getChannel | avg | 14ms | 9ms | -5ms | -35.69
| updatePreferences | avg | 20ms | 13ms | -7ms | -34.35
| unfollowThreadByUser | avg | 41ms | 27ms | -14ms | -34.19
| getChannelStats | avg | 9ms | 6ms | -3ms | -34.17
| getTeamsUnreadForUser | avg | 12ms | 8ms | -4ms | -34.14
| updateReadStateThreadByUser | avg | 98ms | 65ms | -33ms | -33.80
| getChannelsForTeamForUser | avg | 9ms | 6ms | -3ms | -33.07
| getClientConfig | avg | 12ms | 8ms | -4ms | -32.85
| getAllTeams | avg | 6ms | 4ms | -2ms | -31.22
| getChannelMembersForTeamForUser | avg | 10ms | 7ms | -3ms | -30.39
| getPostsForChannelAroundLastUnread | avg | 43ms | 30ms | -13ms | -30.37
| getPreferences | avg | 7ms | 5ms | -2ms | -29.74
| getChannelMember | avg | 10ms | 7ms | -3ms | -29.62
| getJobsByType | avg | 7ms | 5ms | -2ms | -29.52
| getLicenseSelfServeStatus | avg | 89ms | 63ms | -26ms | -29.35
| updateCategoriesForTeamForUser | avg | 116ms | 82ms | -34ms | -29.28
| getUser | avg | 11ms | 8ms | -3ms | -28.20
| removeUserCustomStatus | avg | 317ms | 228ms | -89ms | -28.07
| getTeamMembersForUser | avg | 7ms | 5ms | -2ms | -27.19
| searchGroupChannels | avg | 11ms | 8ms | -3ms | -26.80
| getProfileImage | avg | 79ms | 60ms | -19ms | -23.99
| getCategoriesForTeamForUser | avg | 29ms | 22ms | -7ms | -23.90
| createPost | avg | 691ms | 530ms | -161ms | -23.30
| createGroupChannel | avg | 720ms | 559ms | -161ms | -22.35
| createDirectChannel | avg | 436ms | 339ms | -97ms | -22.23
| createChannel | avg | 35ms | 28ms | -7ms | -19.82
| autocompleteUsers | avg | 71ms | 57ms | -14ms | -19.77
| deletePost | avg | 33ms | 27ms | -6ms | -18.13
| getFileThumbnail | avg | 53ms | 44ms | -9ms | -16.98
| addChannelMember | avg | 433ms | 364ms | -69ms | -15.92
| searchUsers | avg | 59ms | 50ms | -9ms | -15.32
| login | avg | 150ms | 130ms | -20ms | -13.30
| addTeamMember | avg | 1.156s | 1.006s | -150ms | -12.98
| getFilePreview | avg | 64ms | 56ms | -8ms | -12.56
| getPublicChannelsForTeam | avg | 32ms | 28ms | -4ms | -12.52
| searchPostsInTeam | avg | 293ms | 260ms | -33ms | -11.26
| searchAllChannels | avg | 65ms | 58ms | -7ms | -10.81
| createUser | avg | 125ms | 113ms | -12ms | -9.61
| getConfig | avg | 39ms | 36ms | -3ms | -7.61
| uploadFileStream | avg | 462ms | 453ms | -9ms | -1.95
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| handleCheckCWSConnection | p99 | 100ms | 0s | -100ms | -100.50
| updateViewedProductNotices | p99 | 10ms | 0s | -10ms | -100.50
| getProductNotices | p99 | 10ms | 0s | -10ms | -100.43
| updateCategoryForTeamForUser | p99 | 249ms | 0s | -249ms | -100.01
| channelMemberCountsByGroup | p99 | 96ms | 0s | -96ms | -100.00
| deleteDraft | p99 | 48ms | 0s | -48ms | -98.97
| getChannelMembers | p99 | 97ms | 5ms | -92ms | -94.85
| createCategoryForTeamForUser | p99 | 478ms | 50ms | -428ms | -89.63
| getFilteredUsersStats | p99 | 97ms | 25ms | -72ms | -74.22
| logout | p99 | 840ms | 243ms | -597ms | -71.07
| setPostReminder | p99 | 238ms | 92ms | -146ms | -61.22
| getAnalytics | p99 | 247ms | 96ms | -151ms | -61.17
| searchFiles | p99 | 25ms | 10ms | -15ms | -60.36
| getLicenseSelfServeStatus | p99 | 244ms | 100ms | -144ms | -59.02
| getPrevTrialLicense | p99 | 24ms | 10ms | -14ms | -58.42
| createChannel | p99 | 231ms | 98ms | -133ms | -57.70
| getUserStatusesByIds | p99 | 21ms | 9ms | -12ms | -56.42
| createDirectChannel | p99 | 2.093s | 996ms | -1.097s | -52.41
| updateCategoriesForTeamForUser | p99 | 810ms | 415ms | -395ms | -48.76
| getUser | p99 | 169ms | 97ms | -72ms | -42.61
| getClientConfig | p99 | 195ms | 113ms | -82ms | -41.96
| getTeamsUnreadForUser | p99 | 151ms | 88ms | -63ms | -41.63
| unfollowThreadByUser | p99 | 421ms | 246ms | -175ms | -41.59
| getChannel | p99 | 177ms | 105ms | -72ms | -40.65
| getChannelStats | p99 | 159ms | 95ms | -64ms | -40.25
| getPostsForChannel | p99 | 742ms | 445ms | -297ms | -40.04
| uploadFileStream | p99 | 1.818s | 1.162s | -656ms | -36.07
| getTeamsForUser | p99 | 70ms | 46ms | -24ms | -34.18
| getUsersByIds | p99 | 28ms | 19ms | -9ms | -32.68
| createPost | p99 | 3.647s | 2.463s | -1.184s | -32.46
| getPreferences | p99 | 83ms | 56ms | -27ms | -32.46
| getChannelUnread | p99 | 94ms | 64ms | -30ms | -31.96
| getAllTeams | p99 | 88ms | 60ms | -28ms | -31.87
| getChannelMember | p99 | 121ms | 85ms | -36ms | -29.87
| getUsersByNames | p99 | 90ms | 64ms | -26ms | -28.85
| getTeamMembersForUser | p99 | 91ms | 65ms | -26ms | -28.68
| searchPostsInTeam | p99 | 3.421s | 2.476s | -945ms | -27.62
| saveReaction | p99 | 460ms | 333ms | -127ms | -27.61
| getPostThread | p99 | 319ms | 236ms | -83ms | -26.00
| getThreadsForUser | p99 | 95ms | 72ms | -23ms | -24.33
| getChannelMembersForTeamForUser | p99 | 90ms | 69ms | -21ms | -23.25
| getChannelsForTeamForUser | p99 | 92ms | 71ms | -21ms | -22.92
| autocompleteUsers | p99 | 375ms | 294ms | -81ms | -21.59
| getPostsForChannelAroundLastUnread | p99 | 464ms | 369ms | -95ms | -20.47
| viewChannel | p99 | 279ms | 225ms | -54ms | -19.38
| getCategoriesForTeamForUser | p99 | 223ms | 182ms | -41ms | -18.34
| getTeamMember | p99 | 85ms | 71ms | -14ms | -16.46
| searchGroupChannels | p99 | 94ms | 79ms | -15ms | -15.91
| removeUserCustomStatus | p99 | 994ms | 844ms | -150ms | -15.08
| updatePreferences | p99 | 226ms | 194ms | -32ms | -14.17
| getChannelsForUser | p99 | 97ms | 84ms | -13ms | -13.40
| addChannelMember | p99 | 2.159s | 1.9s | -259ms | -12.00
| updateReadStateThreadByUser | p99 | 496ms | 440ms | -56ms | -11.29
| login | p99 | 976ms | 878ms | -98ms | -10.04
| createUser | p99 | 499ms | 458ms | -41ms | -8.21
| getConfig | p99 | 224ms | 208ms | -16ms | -7.14
| getFileThumbnail | p99 | 243ms | 226ms | -17ms | -6.99
| addTeamMember | p99 | 4.815s | 4.496s | -319ms | -6.63
| createGroupChannel | p99 | 2.487s | 2.344s | -143ms | -5.75
| searchUsers | p99 | 242ms | 230ms | -12ms | -4.96
| getPublicChannelsForTeam | p99 | 176ms | 168ms | -8ms | -4.54
| getFilePreview | p99 | 249ms | 240ms | -9ms | -3.61
| getProfileImage | p99 | 468ms | 457ms | -11ms | -2.35
| searchAllChannels | p99 | 247ms | 244ms | -3ms | -1.22
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 5ms | -1ms | -16.921
| |  P99| 66ms| 46ms | -20ms | -30.456
| BotStore.Get |  Avg| 8ms| 4ms | -4ms | -50.520
| |  P99| 48ms| 44ms | -4ms | -8.348
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 137ms| 107ms | -30ms | -21.856
| |  P99| 481ms| 418ms | -63ms | -13.098
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 4ms | -1ms | -21.486
| |  P99| 48ms| 36ms | -12ms | -25.096
| ChannelStore.AnalyticsTypeCount |  Avg| 23ms| 14ms | -9ms | -38.614
| |  P99| 50ms| 47ms | -3ms | -6.055
| ChannelStore.Autocomplete |  Avg| 64ms| 57ms | -7ms | -10.891
| |  P99| 247ms| 244ms | -3ms | -1.215
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 120ms| 119ms | -1ms | -0.836
| |  P99| 245ms| 2.08s | 1.835s | 749.069
| ChannelStore.CreateDirectChannel |  Avg| 47ms| 32ms | -15ms | -32.172
| |  P99| 388ms| 244ms | -144ms | -37.121
| ChannelStore.CreateInitialSidebarCategories |  Avg| 27ms| 22ms | -5ms | -18.298
| |  P99| 253ms| 228ms | -25ms | -9.889
| ChannelStore.CreateSidebarCategory |  Avg| 76ms| 18ms | -58ms | -76.176
| |  P99| 478ms| 25ms | -453ms | -94.869
| ChannelStore.Get |  Avg| 8ms| 5ms | -3ms | -38.473
| |  P99| 83ms| 49ms | -34ms | -41.110
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 24ms| 22ms | -2ms | -8.471
| |  P99| 131ms| 131ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.344
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 41ms| 33ms | -8ms | -19.506
| |  P99| 236ms| 197ms | -39ms | -16.531
| ChannelStore.GetByName |  Avg| 7ms| 5ms | -2ms | -30.337
| |  P99| 67ms| 50ms | -17ms | -25.535
| ChannelStore.GetChannelUnread |  Avg| 8ms| 5ms | -3ms | -36.510
| |  P99| 83ms| 50ms | -33ms | -39.684
| ChannelStore.GetChannels |  Avg| 8ms| 5ms | -3ms | -36.119
| |  P99| 87ms| 63ms | -24ms | -27.586
| ChannelStore.GetChannelsByUser |  Avg| 9ms| 6ms | -3ms | -32.117
| |  P99| 88ms| 49ms | -39ms | -44.256
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 7ms| 4ms | -3ms | -44.630
| |  P99| 77ms| 48ms | -29ms | -37.495
| ChannelStore.GetFileCount |  Avg| 8ms| 5ms | -3ms | -36.623
| |  P99| 79ms| 54ms | -25ms | -31.598
| ChannelStore.GetGuestCount |  Avg| 7ms| 5ms | -2ms | -28.472
| |  P99| 81ms| 55ms | -26ms | -32.037
| ChannelStore.GetMember |  Avg| 8ms| 5ms | -3ms | -39.778
| |  P99| 91ms| 63ms | -28ms | -30.878
| ChannelStore.GetMemberCount |  Avg| 34ms| 28ms | -6ms | -17.594
| |  P99| 212ms| 169ms | -43ms | -20.246
| ChannelStore.GetMemberCountsByGroup |  Avg| 17ms| 0s | -17ms | -102.327
| |  P99| 96ms| 0s | -96ms | -100.001
| ChannelStore.GetMemberForPost |  Avg| 11ms| 8ms | -3ms | -27.953
| |  P99| 82ms| 51ms | -31ms | -37.778
| ChannelStore.GetMemberOnly |  Avg| 5ms| 0s | -5ms | -92.122
| |  P99| 71ms| 0s | -71ms | -100.070
| ChannelStore.GetMembers |  Avg| 17ms| 2ms | -15ms | -86.069
| |  P99| 97ms| 5ms | -92ms | -94.845
| ChannelStore.GetMembersForUser |  Avg| 9ms| 6ms | -3ms | -31.839
| |  P99| 87ms| 64ms | -23ms | -26.427
| ChannelStore.GetMembersForUserWithPagination |  Avg| 25ms| 26ms | 1ms | 4.046
| |  P99| 88ms| 92ms | 4ms | 4.545
| ChannelStore.GetPinnedPostCount |  Avg| 7ms| 4ms | -3ms | -41.715
| |  P99| 84ms| 55ms | -29ms | -34.670
| ChannelStore.GetPublicChannelsForTeam |  Avg| 30ms| 26ms | -4ms | -13.187
| |  P99| 176ms| 168ms | -8ms | -4.537
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 29ms| 22ms | -7ms | -24.235
| |  P99| 220ms| 177ms | -43ms | -19.509
| ChannelStore.GetSidebarCategory |  Avg| 17ms| 16ms | -1ms | -5.837
| |  P99| 201ms| 205ms | 4ms | 1.995
| ChannelStore.GetTeamChannels |  Avg| 35ms| 28ms | -7ms | -19.903
| |  P99| 231ms| 98ms | -133ms | -57.699
| ChannelStore.IncrementMentionCount |  Avg| 5ms| 3ms | -2ms | -40.248
| |  P99| 70ms| 47ms | -23ms | -33.061
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 29ms| 16ms | -13ms | -45.412
| |  P99| 355ms| 99ms | -256ms | -72.115
| ChannelStore.SaveMember |  Avg| 46ms| 37ms | -9ms | -19.714
| |  P99| 358ms| 244ms | -114ms | -31.877
| ChannelStore.SearchGroupChannels |  Avg| 11ms| 8ms | -3ms | -27.088
| |  P99| 94ms| 78ms | -16ms | -17.093
| ChannelStore.Update |  Avg| 19ms| 0s | -19ms | -102.025
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 5ms | -2ms | -27.592
| |  P99| 70ms| 45ms | -25ms | -35.495
| ChannelStore.UpdateSidebarCategories |  Avg| 87ms| 48ms | -39ms | -44.609
| |  P99| 474ms| 225ms | -249ms | -52.559
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 4ms| 2ms | -2ms | -47.934
| |  P99| 63ms| 41ms | -22ms | -34.708
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 7ms| 6ms | -1ms | -13.914
| |  P99| 76ms| 77ms | 1ms | 1.312
| CommandStore.AnalyticsCommandCount |  Avg| 63ms| 0s | -63ms | -100.319
| |  P99| 100ms| 0s | -100ms | -100.503
| CommandWebhookStore.Cleanup |  Avg| 6ms| 1ms | -5ms | -79.292
| |  P99| 24ms| 5ms | -19ms | -77.867
| ComplianceStore.MessageExport |  Avg| 12ms| 10ms | -2ms | -16.818
| |  P99| 100ms| 94ms | -6ms | -6.000
| DraftStore.Get |  Avg| 11ms| 0s | -11ms | -95.787
| |  P99| 49ms| 0s | -49ms | -100.514
| DraftStore.GetDraftsForUser |  Avg| 5ms| 3ms | -2ms | -42.476
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 12ms| 8ms | -4ms | -34.382
| |  P99| 106ms| 81ms | -25ms | -23.659
| FileInfoStore.Get |  Avg| 7ms| 4ms | -3ms | -40.552
| |  P99| 86ms| 59ms | -27ms | -31.398
| FileInfoStore.GetForPost |  Avg| 7ms| 4ms | -3ms | -43.498
| |  P99| 81ms| 45ms | -36ms | -44.332
| FileInfoStore.Save |  Avg| 10ms| 6ms | -4ms | -38.722
| |  P99| 93ms| 62ms | -31ms | -33.173
| FileInfoStore.Search |  Avg| 11ms| 6ms | -5ms | -46.863
| |  P99| 25ms| 10ms | -15ms | -60.362
| FileInfoStore.SetContent |  Avg| 15ms| 12ms | -3ms | -20.234
| |  P99| 153ms| 122ms | -31ms | -20.218
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 3ms | -1ms | -26.724
| |  P99| 49ms| 44ms | -5ms | -10.216
| GroupStore.GetByName |  Avg| 4ms| 3ms | -1ms | -22.508
| |  P99| 61ms| 47ms | -14ms | -22.938
| GroupStore.GetGroups |  Avg| 7ms| 4ms | -3ms | -46.044
| |  P99| 66ms| 46ms | -20ms | -30.122
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 4ms | 1ms | 29.670
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 11ms| 7ms | -4ms | -37.260
| |  P99| 94ms| 88ms | -6ms | -6.366
| JobStore.GetAllByStatus |  Avg| 9ms| 6ms | -3ms | -32.065
| |  P99| 98ms| 82ms | -16ms | -16.371
| JobStore.GetAllByTypePage |  Avg| 7ms| 4ms | -3ms | -45.963
| |  P99| 44ms| 47ms | 3ms | 6.743
| JobStore.GetCountByStatusAndType |  Avg| 7ms| 5ms | -2ms | -30.763
| |  P99| 106ms| 119ms | 13ms | 12.264
| JobStore.GetNewestJobByStatusesAndType |  Avg| 5ms| 4ms | -1ms | -19.593
| |  P99| 48ms| 47ms | -1ms | -2.088
| JobStore.Save |  Avg| 5ms| 7ms | 2ms | 36.400
| |  P99| 42ms| 85ms | 43ms | 101.176
| JobStore.UpdateOptimistically |  Avg| 9ms| 7ms | -2ms | -23.504
| |  P99| 90ms| 66ms | -24ms | -26.685
| JobStore.UpdateStatus |  Avg| 6ms| 3ms | -3ms | -48.567
| |  P99| 69ms| 35ms | -34ms | -48.921
| JobStore.UpdateStatusOptimistically |  Avg| 14ms| 5ms | -9ms | -62.905
| |  P99| 345ms| 34ms | -311ms | -90.145
| LicenseStore.GetAll |  Avg| 5ms| 1ms | -4ms | -75.326
| |  P99| 24ms| 10ms | -14ms | -57.712
| LinkMetadataStore.Get |  Avg| 6ms| 4ms | -2ms | -32.697
| |  P99| 70ms| 45ms | -25ms | -35.965
| LinkMetadataStore.Save |  Avg| 7ms| 4ms | -3ms | -42.231
| |  P99| 82ms| 38ms | -44ms | -53.428
| PluginStore.Delete |  Avg| 3ms| 2ms | -1ms | -31.644
| |  P99| 42ms| 25ms | -17ms | -40.235
| PluginStore.Get |  Avg| 4ms| 3ms | -1ms | -28.273
| |  P99| 41ms| 36ms | -5ms | -12.270
| PluginStore.List |  Avg| 6ms| 5ms | -1ms | -18.005
| |  P99| 45ms| 73ms | 28ms | 61.766
| PluginStore.SetWithOptions |  Avg| 8ms| 6ms | -2ms | -26.593
| |  P99| 87ms| 59ms | -28ms | -32.283
| PostAcknowledgementStore.GetForPost |  Avg| 5ms| 3ms | -2ms | -43.609
| |  P99| 54ms| 40ms | -14ms | -25.749
| PostAcknowledgementStore.GetForPosts |  Avg| 8ms| 5ms | -3ms | -38.086
| |  P99| 93ms| 56ms | -37ms | -39.860
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 2ms | -1ms | -33.986
| |  P99| 24ms| 22ms | -2ms | -8.484
| PostPersistentNotificationStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 40ms | 17ms | 73.593
| PostPersistentNotificationStore.GetSingle |  Avg| 5ms| 3ms | -2ms | -36.615
| |  P99| 53ms| 39ms | -14ms | -26.196
| PostPriorityStore.GetForPost |  Avg| 5ms| 3ms | -2ms | -37.229
| |  P99| 49ms| 40ms | -9ms | -18.501
| PostPriorityStore.GetForPosts |  Avg| 9ms| 5ms | -4ms | -46.937
| |  P99| 94ms| 64ms | -30ms | -31.764
| PostStore.AnalyticsPostCount |  Avg| 481ms| 248ms | -233ms | -48.476
| |  P99| 990ms| 495ms | -495ms | -50.000
| PostStore.Delete |  Avg| 19ms| 16ms | -3ms | -15.655
| |  P99| 92ms| 90ms | -2ms | -2.186
| PostStore.Get |  Avg| 15ms| 10ms | -5ms | -32.763
| |  P99| 178ms| 97ms | -81ms | -45.421
| PostStore.GetEtag |  Avg| 8ms| 5ms | -3ms | -37.544
| |  P99| 89ms| 69ms | -20ms | -22.516
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 3ms | -1ms | -22.698
| |  P99| 52ms| 40ms | -12ms | -22.887
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 3ms | -2ms | -38.741
| |  P99| 71ms| 45ms | -26ms | -36.394
| PostStore.GetPostReminderMetadata |  Avg| 8ms| 4ms | -4ms | -47.519
| |  P99| 77ms| 23ms | -54ms | -70.133
| PostStore.GetPostReminders |  Avg| 9ms| 7ms | -2ms | -22.328
| |  P99| 49ms| 44ms | -5ms | -10.296
| PostStore.GetPosts |  Avg| 7ms| 5ms | -2ms | -30.149
| |  P99| 61ms| 45ms | -16ms | -26.065
| PostStore.GetPostsAfter |  Avg| 9ms| 6ms | -3ms | -33.527
| |  P99| 78ms| 45ms | -33ms | -42.531
| PostStore.GetPostsBefore |  Avg| 10ms| 7ms | -3ms | -29.984
| |  P99| 90ms| 67ms | -23ms | -25.438
| PostStore.GetPostsByThread |  Avg| 11ms| 8ms | -3ms | -26.386
| |  P99| 83ms| 49ms | -34ms | -40.964
| PostStore.GetPostsSince |  Avg| 25ms| 18ms | -7ms | -28.516
| |  P99| 200ms| 125ms | -75ms | -37.588
| PostStore.GetSingle |  Avg| 6ms| 3ms | -3ms | -51.748
| |  P99| 64ms| 43ms | -21ms | -32.885
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 21ms| 15ms | -6ms | -28.560
| |  P99| 227ms| 172ms | -55ms | -24.256
| PostStore.SearchPostsForUser |  Avg| 270ms| 244ms | -26ms | -9.614
| |  P99| 2.497s| 2.457s | -40ms | -1.602
| PostStore.SetPostReminder |  Avg| 12ms| 5ms | -7ms | -58.117
| |  P99| 94ms| 23ms | -71ms | -75.333
| PostStore.Update |  Avg| 20ms| 19ms | -1ms | -5.079
| |  P99| 193ms| 116ms | -77ms | -39.960
| PreferenceStore.DeleteCategoryAndName |  Avg| 17ms| 7ms | -10ms | -58.187
| |  P99| 225ms| 45ms | -180ms | -80.177
| PreferenceStore.Get |  Avg| 8ms| 5ms | -3ms | -38.933
| |  P99| 86ms| 60ms | -26ms | -30.069
| PreferenceStore.GetAll |  Avg| 6ms| 5ms | -1ms | -15.483
| |  P99| 81ms| 52ms | -29ms | -35.730
| PreferenceStore.Save |  Avg| 14ms| 10ms | -4ms | -28.243
| |  P99| 191ms| 123ms | -68ms | -35.607
| ProductNoticesStore.ClearOldNotices |  Avg| 36ms| 35ms | -1ms | -2.788
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 4ms| 6ms | 2ms | 52.335
| |  P99| 10ms| 10ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 49ms| 39ms | -10ms | -20.267
| |  P99| 463ms| 374ms | -89ms | -19.228
| ReactionStore.ExistsOnPost |  Avg| 7ms| 4ms | -3ms | -40.582
| |  P99| 79ms| 45ms | -34ms | -43.066
| ReactionStore.GetForPost |  Avg| 6ms| 4ms | -2ms | -32.579
| |  P99| 68ms| 43ms | -25ms | -36.872
| ReactionStore.GetUniqueCountForPost |  Avg| 6ms| 3ms | -3ms | -50.965
| |  P99| 76ms| 44ms | -32ms | -42.032
| ReactionStore.Save |  Avg| 20ms| 13ms | -7ms | -35.650
| |  P99| 215ms| 147ms | -68ms | -31.582
| RetentionPolicyStore.GetAll |  Avg| 8ms| 5ms | -3ms | -35.437
| |  P99| 25ms| 10ms | -15ms | -61.100
| RetentionPolicyStore.GetCount |  Avg| 7ms| 1ms | -6ms | -91.708
| |  P99| 24ms| 5ms | -19ms | -77.869
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 30ms| 40ms | 10ms | 33.056
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 9ms| 3ms | -6ms | -64.809
| |  P99| 10ms| 5ms | -5ms | -50.251
| SessionStore.AnalyticsSessionCount |  Avg| 81ms| 0s | -81ms | -100.464
| |  P99| 100ms| 0s | -100ms | -100.503
| SessionStore.Get |  Avg| 11ms| 8ms | -3ms | -28.024
| |  P99| 142ms| 93ms | -49ms | -34.491
| SessionStore.GetSessionsExpired |  Avg| 12ms| 5ms | -7ms | -57.229
| |  P99| 49ms| 48ms | -1ms | -2.046
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 6ms| 3ms | -3ms | -54.056
| |  P99| 49ms| 36ms | -13ms | -26.681
| SessionStore.Remove |  Avg| 8ms| 3ms | -5ms | -66.393
| |  P99| 92ms| 21ms | -71ms | -77.174
| SessionStore.Save |  Avg| 11ms| 8ms | -3ms | -28.387
| |  P99| 97ms| 75ms | -22ms | -22.651
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 5ms | -2ms | -29.775
| |  P99| 61ms| 42ms | -19ms | -31.073
| StatusStore.Get |  Avg| 4ms| 3ms | -1ms | -24.908
| |  P99| 49ms| 43ms | -6ms | -12.318
| StatusStore.GetByIds |  Avg| 10ms| 7ms | -3ms | -29.877
| |  P99| 91ms| 69ms | -22ms | -24.196
| StatusStore.SaveOrUpdate |  Avg| 91ms| 61ms | -30ms | -32.827
| |  P99| 981ms| 900ms | -81ms | -8.260
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 15ms| 6ms | -9ms | -61.669
| |  P99| 94ms| 215ms | 121ms | 128.382
| StatusStore.UpdateLastActivityAt |  Avg| 6ms| 4ms | -2ms | -33.733
| |  P99| 59ms| 42ms | -17ms | -28.954
| SystemStore.GetByName |  Avg| 4ms| 2ms | -2ms | -55.085
| |  P99| 53ms| 41ms | -12ms | -22.803
| SystemStore.Save |  Avg| 2ms| 0s | -2ms | -91.135
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 7ms| 4ms | -3ms | -42.979
| |  P99| 25ms| 24ms | -1ms | -4.073
| TeamStore.Get |  Avg| 5ms| 3ms | -2ms | -38.231
| |  P99| 58ms| 41ms | -17ms | -29.437
| TeamStore.GetAllPage |  Avg| 5ms| 3ms | -2ms | -38.385
| |  P99| 73ms| 47ms | -26ms | -35.391
| TeamStore.GetByName |  Avg| 4ms| 2ms | -2ms | -49.583
| |  P99| 53ms| 30ms | -23ms | -43.076
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 6ms| 4ms | -2ms | -31.830
| |  P99| 73ms| 47ms | -26ms | -35.540
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 19ms | -9ms | -32.723
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 4ms | -1ms | -18.908
| |  P99| 68ms| 46ms | -22ms | -32.346
| TeamStore.GetTeamsForUser |  Avg| 6ms| 4ms | -2ms | -34.189
| |  P99| 73ms| 47ms | -26ms | -35.859
| TeamStore.SaveMember |  Avg| 35ms| 32ms | -3ms | -8.528
| |  P99| 221ms| 200ms | -21ms | -9.501
| ThreadStore.Get |  Avg| 7ms| 4ms | -3ms | -41.618
| |  P99| 85ms| 47ms | -38ms | -44.641
| ThreadStore.GetMembershipForUser |  Avg| 6ms| 4ms | -2ms | -32.258
| |  P99| 74ms| 46ms | -28ms | -37.584
| ThreadStore.GetTeamsUnreadForUser |  Avg| 9ms| 6ms | -3ms | -32.841
| |  P99| 92ms| 65ms | -27ms | -29.406
| ThreadStore.GetThreadFollowers |  Avg| 6ms| 3ms | -3ms | -52.326
| |  P99| 55ms| 43ms | -12ms | -21.636
| ThreadStore.GetThreadForUser |  Avg| 13ms| 9ms | -4ms | -31.378
| |  P99| 119ms| 86ms | -33ms | -27.725
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 13ms| 9ms | -4ms | -29.976
| |  P99| 92ms| 71ms | -21ms | -22.734
| ThreadStore.GetThreadsForUser |  Avg| 10ms| 7ms | -3ms | -28.613
| |  P99| 91ms| 67ms | -24ms | -26.466
| ThreadStore.GetTotalThreads |  Avg| 6ms| 4ms | -2ms | -32.085
| |  P99| 72ms| 45ms | -27ms | -37.550
| ThreadStore.GetTotalUnreadMentions |  Avg| 6ms| 4ms | -2ms | -31.618
| |  P99| 72ms| 45ms | -27ms | -37.680
| ThreadStore.GetTotalUnreadThreads |  Avg| 6ms| 4ms | -2ms | -31.731
| |  P99| 72ms| 46ms | -26ms | -36.138
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 7ms| 4ms | -3ms | -44.949
| |  P99| 74ms| 47ms | -27ms | -36.445
| ThreadStore.MaintainMembership |  Avg| 11ms| 7ms | -4ms | -35.631
| |  P99| 149ms| 86ms | -63ms | -42.246
| ThreadStore.MarkAllAsReadByChannels |  Avg| 6ms| 3ms | -3ms | -47.939
| |  P99| 82ms| 46ms | -36ms | -43.914
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 8ms | 4ms | 97.243
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 6ms| 4ms | -2ms | -31.882
| |  P99| 61ms| 39ms | -22ms | -36.097
| ThreadStore.UpdateMembership |  Avg| 6ms| 4ms | -2ms | -33.897
| |  P99| 55ms| 40ms | -15ms | -27.386
| TokenStore.Cleanup |  Avg| 9ms| 1ms | -8ms | -86.322
| |  P99| 25ms| 5ms | -20ms | -80.971
| UserAccessTokenStore.GetByToken |  Avg| 5ms| 4ms | -1ms | -20.267
| |  P99| 40ms| 40ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 45ms| 32ms | -13ms | -28.707
| |  P99| 99ms| 96ms | -3ms | -3.038
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 4ms| 1ms | -3ms | -83.397
| |  P99| 10ms| 5ms | -5ms | -51.092
| UserStore.AutocompleteUsersInChannel |  Avg| 82ms| 68ms | -14ms | -17.012
| |  P99| 415ms| 370ms | -45ms | -10.836
| UserStore.Count |  Avg| 41ms| 19ms | -22ms | -54.074
| |  P99| 98ms| 87ms | -11ms | -11.171
| UserStore.Get |  Avg| 5ms| 3ms | -2ms | -40.764
| |  P99| 67ms| 43ms | -24ms | -36.035
| UserStore.GetAllProfiles |  Avg| 6ms| 5ms | -1ms | -17.321
| |  P99| 47ms| 38ms | -9ms | -19.012
| UserStore.GetAllProfilesInChannel |  Avg| 403ms| 343ms | -60ms | -14.875
| |  P99| 2.086s| 1.396s | -690ms | -33.077
| UserStore.GetByUsername |  Avg| 6ms| 5ms | -1ms | -16.604
| |  P99| 47ms| 49ms | 2ms | 4.221
| UserStore.GetForLogin |  Avg| 5ms| 4ms | -1ms | -19.149
| |  P99| 65ms| 46ms | -19ms | -29.108
| UserStore.GetMany |  Avg| 3ms| 6ms | 3ms | 94.908
| |  P99| 23ms| 89ms | 66ms | 282.654
| UserStore.GetProfileByIds |  Avg| 8ms| 5ms | -3ms | -39.540
| |  P99| 87ms| 62ms | -25ms | -28.698
| UserStore.GetProfilesByUsernames |  Avg| 8ms| 5ms | -3ms | -35.531
| |  P99| 89ms| 62ms | -27ms | -30.490
| UserStore.GetProfilesInChannel |  Avg| 253ms| 251ms | -2ms | -0.790
| |  P99| 940ms| 933ms | -7ms | -0.745
| UserStore.GetUnreadCount |  Avg| 6ms| 4ms | -2ms | -30.879
| |  P99| 69ms| 46ms | -23ms | -33.552
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 24ms | -7ms | -22.558
| UserStore.Save |  Avg| 79ms| 75ms | -4ms | -5.068
| |  P99| 247ms| 237ms | -10ms | -4.055
| UserStore.Search |  Avg| 56ms| 48ms | -8ms | -14.200
| |  P99| 241ms| 227ms | -14ms | -5.819
| UserStore.Update |  Avg| 20ms| 13ms | -7ms | -34.987
| |  P99| 244ms| 99ms | -145ms | -59.501
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 5ms | -1ms | -15.692
| |  P99| 68ms| 47ms | -21ms | -30.708
| UserStore.UpdateLastLogin |  Avg| 6ms| 5ms | -1ms | -15.511
| |  P99| 48ms| 39ms | -9ms | -18.933
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 40ms | -7ms | -14.817
| UserTermsOfServiceStore.GetByUser |  Avg| 5ms| 3ms | -2ms | -42.904
| |  P99| 62ms| 44ms | -18ms | -28.926
| WebhookStore.AnalyticsIncomingCount |  Avg| 58ms| 0s | -58ms | -99.702
| |  P99| 100ms| 0s | -100ms | -100.503
| WebhookStore.AnalyticsOutgoingCount |  Avg| 58ms| 0s | -58ms | -99.741
| |  P99| 100ms| 0s | -100ms | -100.503
| WebhookStore.GetOutgoingByTeam |  Avg| 9ms| 7ms | -2ms | -21.665
| |  P99| 90ms| 73ms | -17ms | -18.853
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 433ms| 364ms | -69ms | -15.917
| | P99| 2.159s| 1.9s | -259ms | -11.996
| addTeamMember | Avg| 1.156s| 1.006s | -150ms | -12.979
| | P99| 4.815s| 4.496s | -319ms | -6.625
| autocompleteChannelsForTeamForSearch | Avg| 120ms| 120ms | 0s | 0.000
| | P99| 245ms| 2.08s | 1.835s | 748.774
| autocompleteUsers | Avg| 71ms| 57ms | -14ms | -19.765
| | P99| 375ms| 294ms | -81ms | -21.592
| channelMemberCountsByGroup | Avg| 18ms| 0s | -18ms | -102.412
| | P99| 96ms| 0s | -96ms | -100.001
| createCategoryForTeamForUser | Avg| 116ms| 24ms | -92ms | -79.513
| | P99| 478ms| 50ms | -428ms | -89.634
| createChannel | Avg| 35ms| 28ms | -7ms | -19.818
| | P99| 231ms| 98ms | -133ms | -57.699
| createDirectChannel | Avg| 436ms| 339ms | -97ms | -22.228
| | P99| 2.093s| 996ms | -1.097s | -52.405
| createGroupChannel | Avg| 720ms| 559ms | -161ms | -22.351
| | P99| 2.487s| 2.344s | -143ms | -5.751
| createPost | Avg| 691ms| 530ms | -161ms | -23.299
| | P99| 3.647s| 2.463s | -1.184s | -32.464
| createUser | Avg| 125ms| 113ms | -12ms | -9.613
| | P99| 499ms| 458ms | -41ms | -8.209
| deleteDraft | Avg| 10ms| 0s | -10ms | -97.805
| | P99| 48ms| 0s | -48ms | -98.970
| deletePost | Avg| 33ms| 27ms | -6ms | -18.129
| | P99| 97ms| 221ms | 124ms | 127.616
| followThreadByUser | Avg| 30ms| 36ms | 6ms | 20.198
| | P99| 97ms| 223ms | 126ms | 129.563
| getAllTeams | Avg| 6ms| 4ms | -2ms | -31.218
| | P99| 88ms| 60ms | -28ms | -31.867
| getAnalytics | Avg| 97ms| 32ms | -65ms | -67.189
| | P99| 247ms| 96ms | -151ms | -61.172
| getCategoriesForTeamForUser | Avg| 29ms| 22ms | -7ms | -23.901
| | P99| 223ms| 182ms | -41ms | -18.345
| getChannel | Avg| 14ms| 9ms | -5ms | -35.686
| | P99| 177ms| 105ms | -72ms | -40.654
| getChannelMember | Avg| 10ms| 7ms | -3ms | -29.621
| | P99| 121ms| 85ms | -36ms | -29.874
| getChannelMembers | Avg| 18ms| 3ms | -15ms | -82.679
| | P99| 97ms| 5ms | -92ms | -94.845
| getChannelMembersForTeamForUser | Avg| 10ms| 7ms | -3ms | -30.390
| | P99| 90ms| 69ms | -21ms | -23.253
| getChannelMembersForUser | Avg| 31ms| 32ms | 1ms | 3.183
| | P99| 99ms| 99ms | 0s | 0.000
| getChannelStats | Avg| 9ms| 6ms | -3ms | -34.168
| | P99| 159ms| 95ms | -64ms | -40.250
| getChannelUnread | Avg| 10ms| 6ms | -4ms | -41.363
| | P99| 94ms| 64ms | -30ms | -31.963
| getChannelsForTeamForUser | Avg| 9ms| 6ms | -3ms | -33.070
| | P99| 92ms| 71ms | -21ms | -22.919
| getChannelsForUser | Avg| 11ms| 7ms | -4ms | -37.777
| | P99| 97ms| 84ms | -13ms | -13.403
| getClientConfig | Avg| 12ms| 8ms | -4ms | -32.853
| | P99| 195ms| 113ms | -82ms | -41.965
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 39ms| 36ms | -3ms | -7.614
| | P99| 224ms| 208ms | -16ms | -7.135
| getFilePreview | Avg| 64ms| 56ms | -8ms | -12.564
| | P99| 249ms| 240ms | -9ms | -3.612
| getFileThumbnail | Avg| 53ms| 44ms | -9ms | -16.978
| | P99| 243ms| 226ms | -17ms | -6.986
| getFilteredUsersStats | Avg| 36ms| 19ms | -17ms | -47.305
| | P99| 97ms| 25ms | -72ms | -74.220
| getGroups | Avg| 2ms| 5ms | 3ms | 143.815
| | P99| 5ms| 24ms | 19ms | 383.838
| getJobsByType | Avg| 7ms| 5ms | -2ms | -29.517
| | P99| 45ms| 47ms | 2ms | 4.470
| getLicenseSelfServeStatus | Avg| 89ms| 63ms | -26ms | -29.346
| | P99| 244ms| 100ms | -144ms | -59.016
| getPostThread | Avg| 38ms| 24ms | -14ms | -36.651
| | P99| 319ms| 236ms | -83ms | -26.004
| getPostsForChannel | Avg| 71ms| 44ms | -27ms | -37.769
| | P99| 742ms| 445ms | -297ms | -40.036
| getPostsForChannelAroundLastUnread | Avg| 43ms| 30ms | -13ms | -30.367
| | P99| 464ms| 369ms | -95ms | -20.474
| getPreferences | Avg| 7ms| 5ms | -2ms | -29.736
| | P99| 83ms| 56ms | -27ms | -32.457
| getPrevTrialLicense | Avg| 5ms| 2ms | -3ms | -58.763
| | P99| 24ms| 10ms | -14ms | -58.424
| getProductNotices | Avg| 7ms| 0s | -7ms | -94.313
| | P99| 10ms| 0s | -10ms | -100.426
| getProfileImage | Avg| 79ms| 60ms | -19ms | -23.989
| | P99| 468ms| 457ms | -11ms | -2.350
| getPublicChannelsForTeam | Avg| 32ms| 28ms | -4ms | -12.523
| | P99| 176ms| 168ms | -8ms | -4.537
| getRolesByNames | Avg| 1ms| 2ms | 1ms | 92.300
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 6ms| 5ms | -1ms | -15.387
| | P99| 85ms| 71ms | -14ms | -16.456
| getTeamMembersForUser | Avg| 7ms| 5ms | -2ms | -27.190
| | P99| 91ms| 65ms | -26ms | -28.680
| getTeamsForUser | Avg| 5ms| 4ms | -1ms | -18.381
| | P99| 70ms| 46ms | -24ms | -34.179
| getTeamsUnreadForUser | Avg| 12ms| 8ms | -4ms | -34.138
| | P99| 151ms| 88ms | -63ms | -41.634
| getThreadsForUser | Avg| 11ms| 7ms | -4ms | -36.844
| | P99| 95ms| 72ms | -23ms | -24.327
| getUser | Avg| 11ms| 8ms | -3ms | -28.196
| | P99| 169ms| 97ms | -72ms | -42.609
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 21ms| 9ms | -12ms | -56.422
| getUsers | Avg| 57ms| 70ms | 13ms | 22.620
| | P99| 708ms| 875ms | 167ms | 23.600
| getUsersByIds | Avg| 3ms| 2ms | -1ms | -38.744
| | P99| 28ms| 19ms | -9ms | -32.683
| getUsersByNames | Avg| 9ms| 5ms | -4ms | -45.434
| | P99| 90ms| 64ms | -26ms | -28.848
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 93ms| 0s | -93ms | -100.462
| | P99| 100ms| 0s | -100ms | -100.503
| login | Avg| 150ms| 130ms | -20ms | -13.305
| | P99| 976ms| 878ms | -98ms | -10.036
| logout | Avg| 138ms| 79ms | -59ms | -42.687
| | P99| 840ms| 243ms | -597ms | -71.073
| patchPost | Avg| 94ms| 147ms | 53ms | 56.616
| | P99| 475ms| 2.849s | 2.374s | 499.785
| removeUserCustomStatus | Avg| 317ms| 228ms | -89ms | -28.067
| | P99| 994ms| 844ms | -150ms | -15.085
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 62ms| 38ms | -24ms | -38.965
| | P99| 460ms| 333ms | -127ms | -27.608
| searchAllChannels | Avg| 65ms| 58ms | -7ms | -10.814
| | P99| 247ms| 244ms | -3ms | -1.215
| searchFiles | Avg| 16ms| 8ms | -8ms | -51.497
| | P99| 25ms| 10ms | -15ms | -60.362
| searchGroupChannels | Avg| 11ms| 8ms | -3ms | -26.800
| | P99| 94ms| 79ms | -15ms | -15.913
| searchPostsInTeam | Avg| 293ms| 260ms | -33ms | -11.262
| | P99| 3.421s| 2.476s | -945ms | -27.621
| searchUsers | Avg| 59ms| 50ms | -9ms | -15.322
| | P99| 242ms| 230ms | -12ms | -4.956
| setPostReminder | Avg| 41ms| 24ms | -17ms | -41.930
| | P99| 238ms| 92ms | -146ms | -61.217
| unfollowThreadByUser | Avg| 41ms| 27ms | -14ms | -34.195
| | P99| 421ms| 246ms | -175ms | -41.586
| updateCategoriesForTeamForUser | Avg| 116ms| 82ms | -34ms | -29.281
| | P99| 810ms| 415ms | -395ms | -48.765
| updateCategoryForTeamForUser | Avg| 200ms| 0s | -200ms | -100.082
| | P99| 249ms| 0s | -249ms | -100.014
| updatePreferences | Avg| 20ms| 13ms | -7ms | -34.347
| | P99| 226ms| 194ms | -32ms | -14.173
| updateReadStateAllThreadsByUser | Avg| 4ms| 9ms | 5ms | 118.863
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 98ms| 65ms | -33ms | -33.796
| | P99| 496ms| 440ms | -56ms | -11.290
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| updateViewedProductNotices | Avg| 7ms| 0s | -7ms | -94.993
| | P99| 10ms| 0s | -10ms | -100.503
| uploadFileStream | Avg| 462ms| 453ms | -9ms | -1.947
| | P99| 1.818s| 1.162s | -656ms | -36.074
| viewChannel | Avg| 32ms| 20ms | -12ms | -37.731
| | P99| 279ms| 225ms | -54ms | -19.378
