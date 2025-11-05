### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 8ms | 556ms | 548ms | 6981.75
| CommandWebhookStore.Cleanup | avg | 1ms | 16ms | 15ms | 1014.53
| ChannelStore.CreateSidebarCategory | avg | 19ms | 172ms | 153ms | 786.05
| TokenStore.Cleanup | avg | 2ms | 14ms | 12ms | 641.72
| ChannelBookmarkStore.UpdateSortOrder | avg | 26ms | 59ms | 33ms | 125.35
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 13ms | 21ms | 8ms | 61.10
| ChannelStore.GetTeamChannels | avg | 36ms | 54ms | 18ms | 49.81
| PostStore.GetPostReminderMetadata | avg | 13ms | 19ms | 6ms | 45.60
| PreferenceStore.DeleteCategoryAndName | avg | 12ms | 17ms | 5ms | 43.35
| ScheduledPostStore.GetPendingScheduledPosts | avg | 25ms | 35ms | 10ms | 40.23
| JobStore.UpdateStatus | avg | 8ms | 11ms | 3ms | 38.06
| JobStore.UpdateStatusOptimistically | avg | 10ms | 13ms | 3ms | 29.97
| PluginStore.List | avg | 14ms | 16ms | 2ms | 13.82
| StatusStore.UpdateExpiredDNDStatuses | avg | 17ms | 19ms | 2ms | 11.61
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 25ms | 2.396s | 2.371s | 9599.19
| CommandWebhookStore.Cleanup | p99 | 5ms | 98ms | 93ms | 1878.75
| ChannelStore.CreateSidebarCategory | p99 | 49ms | 494ms | 445ms | 912.82
| TokenStore.Cleanup | p99 | 10ms | 98ms | 88ms | 907.19
| JobStore.UpdateStatus | p99 | 75ms | 210ms | 135ms | 179.99
| PostStore.GetPostReminderMetadata | p99 | 92ms | 218ms | 126ms | 136.74
| JobStore.UpdateOptimistically | p99 | 89ms | 189ms | 100ms | 111.86
| JobStore.UpdateStatusOptimistically | p99 | 90ms | 190ms | 100ms | 111.11
| ChannelStore.GetTeamChannels | p99 | 230ms | 438ms | 208ms | 90.24
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 232ms | 425ms | 193ms | 83.37
| PluginStore.List | p99 | 193ms | 350ms | 157ms | 81.35
| ChannelStore.AutocompleteInTeamForSearch | p99 | 492ms | 720ms | 228ms | 46.29
| ChannelStore.Save | p99 | 443ms | 615ms | 172ms | 38.83
| SessionStore.Remove | p99 | 69ms | 92ms | 23ms | 33.33
| PostPersistentNotificationStore.Get | p99 | 70ms | 88ms | 18ms | 25.72
| FileInfoStore.SetContent | p99 | 238ms | 272ms | 34ms | 14.27
| ClusterDiscoveryStore.SetLastPingAt | p99 | 169ms | 193ms | 24ms | 14.20
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 85ms | 96ms | 11ms | 12.94
| PostPersistentNotificationStore.DeleteExpired | p99 | 160ms | 178ms | 18ms | 11.25
| StatusStore.UpdateExpiredDNDStatuses | p99 | 202ms | 221ms | 19ms | 9.38
| ChannelStore.GetPublicChannelsForTeam | p99 | 215ms | 233ms | 18ms | 8.37
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 458ms | 484ms | 26ms | 5.67
| PostStore.GetPostReminders | p99 | 407ms | 425ms | 18ms | 4.42
| PreferenceStore.DeleteCategoryAndName | p99 | 92ms | 96ms | 4ms | 4.32
| PostStore.Delete | p99 | 425ms | 443ms | 18ms | 4.24
| JobStore.GetCountByStatusAndType | p99 | 216ms | 224ms | 8ms | 3.71
| ChannelBookmarkStore.UpdateSortOrder | p99 | 239ms | 245ms | 6ms | 2.51
| StatusStore.UpdateLastActivityAt | p99 | 112ms | 114ms | 2ms | 1.79
| PostStore.Update | p99 | 245ms | 248ms | 3ms | 1.22
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCountByTeam | avg | 3ms | 0s | -3ms | -115.83
| ChannelStore.GetMany | avg | 3ms | 0s | -3ms | -113.45
| TeamStore.AnalyticsTeamCount | avg | 3ms | 0s | -3ms | -108.27
| UserStore.AnalyticsGetInactiveUsersCount | avg | 12ms | 0s | -12ms | -104.24
| ChannelStore.GetMemberCountsByGroup | avg | 27ms | 0s | -27ms | -101.77
| BotStore.GetAll | avg | 36ms | 0s | -36ms | -101.19
| JobStore.GetAllByTypePage | avg | 29ms | 0s | -29ms | -100.84
| JobStore.GetAllByTypesAndStatusesPage | avg | 2ms | 0s | -2ms | -100.58
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring | avg | 44ms | 0s | -44ms | -100.38
| PluginStore.SetWithOptions | avg | 90ms | 0s | -90ms | -100.35
| PluginStore.Delete | avg | 35ms | 0s | -35ms | -100.08
| UserStore.AnalyticsActiveCount | avg | 24ms | 0s | -24ms | -99.58
| RetentionPolicyStore.GetAll | avg | 29ms | 0s | -29ms | -98.99
| RetentionPolicyStore.GetCount | avg | 34ms | 0s | -34ms | -98.95
| ChannelStore.AnalyticsCountAll | avg | 22ms | 0s | -22ms | -98.70
| LicenseStore.GetAll | avg | 5ms | 0s | -5ms | -98.38
| ThreadStore.MarkAllAsReadByTeam | avg | 72ms | 8ms | -64ms | -88.50
| SessionStore.GetSessionsExpired | avg | 16ms | 5ms | -11ms | -66.69
| RoleStore.ChannelHigherScopedPermissions | avg | 38ms | 13ms | -25ms | -66.17
| UserStore.GetMany | avg | 20ms | 8ms | -12ms | -61.37
| ChannelStore.GetMembers | avg | 66ms | 26ms | -40ms | -60.19
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 163ms | 67ms | -96ms | -58.86
| UserStore.GetProfilesInChannel | avg | 24ms | 11ms | -13ms | -55.15
| ChannelBookmarkStore.Save | avg | 67ms | 32ms | -35ms | -52.28
| RoleStore.GetByNames | avg | 52ms | 27ms | -25ms | -47.85
| ChannelStore.GetSidebarCategory | avg | 45ms | 25ms | -20ms | -44.57
| LinkMetadataStore.Save | avg | 14ms | 8ms | -6ms | -43.18
| JobStore.GetNewestJobByStatusesAndType | avg | 19ms | 11ms | -8ms | -41.09
| PostStore.SetPostReminder | avg | 36ms | 23ms | -13ms | -36.23
| ChannelBookmarkStore.Delete | avg | 18ms | 12ms | -6ms | -33.90
| ChannelBookmarkStore.Get | avg | 13ms | 9ms | -4ms | -30.00
| UserAccessTokenStore.GetByToken | avg | 17ms | 12ms | -5ms | -29.97
| JobStore.GetCountByStatusAndType | avg | 24ms | 17ms | -7ms | -29.58
| PostStore.AnalyticsPostCount | avg | 273ms | 198ms | -75ms | -27.44
| PostPriorityStore.GetForPost | avg | 12ms | 9ms | -3ms | -25.79
| PostAcknowledgementStore.GetForPost | avg | 12ms | 9ms | -3ms | -24.17
| EmojiStore.GetByName | avg | 15ms | 12ms | -3ms | -20.63
| UserStore.Get | avg | 15ms | 12ms | -3ms | -20.43
| UserStore.GetByUsername | avg | 20ms | 16ms | -4ms | -19.66
| JobStore.GetAllByStatus | avg | 21ms | 17ms | -4ms | -19.42
| PostStore.Update | avg | 36ms | 29ms | -7ms | -19.30
| UserStore.GetAllProfiles | avg | 11ms | 9ms | -2ms | -18.94
| ChannelStore.IncrementMentionCount | avg | 11ms | 9ms | -2ms | -18.67
| ChannelStore.GetMember | avg | 11ms | 9ms | -2ms | -17.82
| ChannelStore.SearchGroupChannels | avg | 23ms | 19ms | -4ms | -17.77
| PostPriorityStore.GetForPosts | avg | 23ms | 19ms | -4ms | -17.72
| UserTermsOfServiceStore.GetByUser | avg | 12ms | 10ms | -2ms | -17.18
| ThreadStore.GetTeamsUnreadForUser | avg | 18ms | 15ms | -3ms | -16.96
| UserStore.GetProfileByIds | avg | 18ms | 15ms | -3ms | -16.79
| ChannelStore.CreateInitialSidebarCategories | avg | 43ms | 36ms | -7ms | -16.44
| TeamStore.GetTeamsForUser | avg | 13ms | 11ms | -2ms | -15.93
| ChannelStore.GetMembersForUser | avg | 19ms | 16ms | -3ms | -15.92
| ThreadStore.GetTotalUnreadThreads | avg | 13ms | 11ms | -2ms | -15.82
| ThreadStore.GetTotalThreads | avg | 13ms | 11ms | -2ms | -15.78
| TeamStore.GetAllPage | avg | 13ms | 11ms | -2ms | -15.69
| TeamStore.GetTeamsByUserId | avg | 13ms | 11ms | -2ms | -15.67
| PropertyValueStore.SearchPropertyValues | avg | 19ms | 16ms | -3ms | -15.58
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 13ms | 11ms | -2ms | -15.42
| ChannelStore.CreateDirectChannel | avg | 98ms | 83ms | -15ms | -15.37
| TeamStore.Get | avg | 13ms | 11ms | -2ms | -15.36
| TeamStore.GetChannelUnreadsForAllTeams | avg | 13ms | 11ms | -2ms | -15.13
| ThreadStore.GetThreadFollowers | avg | 13ms | 11ms | -2ms | -15.11
| ReactionStore.GetForPost | avg | 14ms | 12ms | -2ms | -14.69
| PostStore.GetSingle | avg | 14ms | 12ms | -2ms | -14.61
| PreferenceStore.Save | avg | 34ms | 29ms | -5ms | -14.53
| ChannelStore.GetMembersForUserWithPagination | avg | 14ms | 12ms | -2ms | -14.42
| TeamStore.GetTotalMemberCount | avg | 70ms | 60ms | -10ms | -14.23
| LinkMetadataStore.Get | avg | 14ms | 12ms | -2ms | -14.20
| ThreadStore.Get | avg | 14ms | 12ms | -2ms | -14.12
| ProductNoticesStore.ClearOldNotices | avg | 43ms | 37ms | -6ms | -14.05
| PreferenceStore.GetAll | avg | 14ms | 12ms | -2ms | -13.97
| ChannelStore.Get | avg | 29ms | 25ms | -4ms | -13.85
| DraftStore.Get | avg | 22ms | 19ms | -3ms | -13.80
| BotStore.Get | avg | 15ms | 13ms | -2ms | -13.77
| PostAcknowledgementStore.GetForPosts | avg | 22ms | 19ms | -3ms | -13.75
| ThreadStore.GetThreadsForUser | avg | 22ms | 19ms | -3ms | -13.70
| ChannelStore.SaveMember | avg | 81ms | 70ms | -11ms | -13.62
| DraftStore.GetDraftsForUser | avg | 22ms | 19ms | -3ms | -13.52
| PostStore.Save | avg | 45ms | 39ms | -6ms | -13.44
| DraftStore.Delete | avg | 15ms | 13ms | -2ms | -13.43
| GroupStore.GetGroups | avg | 15ms | 13ms | -2ms | -13.39
| StatusStore.SaveOrUpdate | avg | 15ms | 13ms | -2ms | -13.34
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 15ms | 13ms | -2ms | -13.26
| ThreadStore.GetMembershipForUser | avg | 15ms | 13ms | -2ms | -13.15
| EmojiStore.GetMultipleByName | avg | 23ms | 20ms | -3ms | -13.11
| PostStore.Get | avg | 38ms | 33ms | -5ms | -13.10
| StatusStore.Get | avg | 15ms | 13ms | -2ms | -12.99
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 15ms | 13ms | -2ms | -12.92
| ChannelStore.GetMemberForPost | avg | 24ms | 21ms | -3ms | -12.69
| SessionStore.Get | avg | 24ms | 21ms | -3ms | -12.65
| PostStore.GetPostsAfter | avg | 16ms | 14ms | -2ms | -12.58
| ThreadStore.MaintainMembership | avg | 24ms | 21ms | -3ms | -12.57
| StatusStore.GetByIds | avg | 24ms | 21ms | -3ms | -12.44
| ChannelStore.GetPinnedPostCount | avg | 16ms | 14ms | -2ms | -12.37
| ChannelStore.GetByName | avg | 16ms | 14ms | -2ms | -12.29
| ChannelStore.GetFileCount | avg | 16ms | 14ms | -2ms | -12.26
| ChannelStore.GetGuestCount | avg | 16ms | 14ms | -2ms | -12.18
| FileInfoStore.GetForPost | avg | 16ms | 14ms | -2ms | -12.16
| FileInfoStore.GetByIds | avg | 17ms | 15ms | -2ms | -12.10
| ChannelStore.GetAllChannelMembersForUser | avg | 17ms | 15ms | -2ms | -11.94
| ProductNoticesStore.View | avg | 111ms | 98ms | -13ms | -11.69
| PreferenceStore.Get | avg | 17ms | 15ms | -2ms | -11.44
| UserStore.GetProfilesByUsernames | avg | 18ms | 16ms | -2ms | -10.98
| PostStore.GetEtag | avg | 18ms | 16ms | -2ms | -10.86
| ChannelStore.UpdateSidebarCategories | avg | 139ms | 124ms | -15ms | -10.83
| SessionStore.Save | avg | 19ms | 17ms | -2ms | -10.48
| ChannelStore.GetChannels | avg | 19ms | 17ms | -2ms | -10.27
| PostStore.GetPostsBefore | avg | 20ms | 18ms | -2ms | -10.14
| PostStore.SearchPostsForUser | avg | 208ms | 187ms | -21ms | -10.11
| StatusStore.SaveOrUpdateMany | avg | 20ms | 18ms | -2ms | -10.06
| TeamStore.SaveMember | avg | 41ms | 37ms | -4ms | -9.72
| WebhookStore.GetOutgoingByTeam | avg | 21ms | 19ms | -2ms | -9.65
| ChannelStore.GetMemberCount | avg | 43ms | 39ms | -4ms | -9.40
| PostStore.GetPostsSince | avg | 33ms | 30ms | -3ms | -9.14
| UserStore.GetAllProfilesInChannel | avg | 418ms | 380ms | -38ms | -9.10
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 22ms | 20ms | -2ms | -8.97
| ThreadStore.GetThreadUnreadReplyCount | avg | 26ms | 24ms | -2ms | -7.83
| ThreadStore.GetThreadForUser | avg | 26ms | 24ms | -2ms | -7.61
| UserStore.Count | avg | 28ms | 26ms | -2ms | -7.22
| ChannelStore.Autocomplete | avg | 57ms | 53ms | -4ms | -7.06
| TeamStore.GetActiveMemberCount | avg | 75ms | 70ms | -5ms | -6.64
| UserStore.Search | avg | 55ms | 52ms | -3ms | -5.44
| UserStore.AutocompleteUsersInChannel | avg | 81ms | 77ms | -4ms | -4.91
| ChannelStore.AutocompleteInTeamForSearch | avg | 84ms | 80ms | -4ms | -4.73
| ChannelStore.Save | avg | 53ms | 51ms | -2ms | -3.79
| UserStore.Save | avg | 189ms | 184ms | -5ms | -2.64
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | p99 | 50ms | 0s | -50ms | -101.01
| PostStore.AnalyticsPostCountByTeam | p99 | 5ms | 0s | -5ms | -101.01
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetAllByTypesAndStatusesPage | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 0s | -5ms | -100.94
| ChannelStore.GetMany | p99 | 5ms | 0s | -5ms | -100.92
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.AnalyticsCountAll | p99 | 25ms | 0s | -25ms | -100.56
| UserStore.AnalyticsActiveCount | p99 | 25ms | 0s | -25ms | -100.56
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring | p99 | 50ms | 0s | -50ms | -100.50
| BotStore.GetAll | p99 | 244ms | 0s | -244ms | -100.00
| PluginStore.Delete | p99 | 98ms | 0s | -98ms | -100.00
| PluginStore.SetWithOptions | p99 | 247ms | 0s | -247ms | -100.00
| RetentionPolicyStore.GetCount | p99 | 99ms | 0s | -99ms | -100.00
| ChannelStore.GetMemberCountsByGroup | p99 | 97ms | 0s | -97ms | -100.00
| JobStore.GetAllByTypePage | p99 | 97ms | 0s | -97ms | -99.49
| LicenseStore.GetAll | p99 | 24ms | 0s | -24ms | -98.36
| ThreadStore.MarkAllAsReadByTeam | p99 | 243ms | 48ms | -195ms | -80.16
| RoleStore.ChannelHigherScopedPermissions | p99 | 415ms | 85ms | -330ms | -79.60
| ChannelBookmarkStore.Delete | p99 | 238ms | 49ms | -189ms | -79.41
| ChannelStore.GetMembers | p99 | 470ms | 98ms | -372ms | -79.15
| ChannelBookmarkStore.Get | p99 | 225ms | 48ms | -177ms | -78.84
| SessionStore.GetSessionsExpired | p99 | 96ms | 23ms | -73ms | -75.84
| ChannelBookmarkStore.Save | p99 | 865ms | 234ms | -631ms | -72.95
| ChannelStore.GetSidebarCategory | p99 | 830ms | 242ms | -588ms | -70.84
| UserStore.GetMany | p99 | 216ms | 85ms | -131ms | -60.70
| UserStore.GetProfilesInChannel | p99 | 225ms | 92ms | -133ms | -59.24
| RoleStore.GetByNames | p99 | 479ms | 198ms | -281ms | -58.68
| EmojiStore.GetMultipleByName | p99 | 229ms | 98ms | -131ms | -57.20
| UserAccessTokenStore.GetByToken | p99 | 219ms | 94ms | -125ms | -56.95
| LinkMetadataStore.Save | p99 | 178ms | 80ms | -98ms | -55.06
| UserStore.GetProfilesNotInChannel | p99 | 211ms | 96ms | -115ms | -54.50
| PostAcknowledgementStore.GetForPost | p99 | 189ms | 92ms | -97ms | -51.32
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 50ms | -49ms | -49.49
| PostStore.AnalyticsPostCount | p99 | 980ms | 496ms | -484ms | -49.39
| JobStore.GetNewestJobByStatusesAndType | p99 | 233ms | 123ms | -110ms | -47.26
| PostStore.SetPostReminder | p99 | 357ms | 202ms | -155ms | -43.36
| PostPriorityStore.GetForPost | p99 | 156ms | 96ms | -60ms | -38.46
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 164ms | 105ms | -59ms | -36.04
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 146ms | 95ms | -51ms | -34.82
| ChannelStore.SaveMember | p99 | 815ms | 541ms | -274ms | -33.61
| ThreadStore.MarkAllAsReadByChannels | p99 | 150ms | 100ms | -50ms | -33.22
| ChannelStore.GetMemberLastViewedAt | p99 | 145ms | 100ms | -45ms | -31.11
| ChannelStore.GetMember | p99 | 155ms | 109ms | -46ms | -29.66
| UserStore.GetAllProfiles | p99 | 133ms | 95ms | -38ms | -28.60
| JobStore.Save | p99 | 175ms | 125ms | -50ms | -28.57
| UserTermsOfServiceStore.GetByUser | p99 | 173ms | 126ms | -47ms | -27.13
| ThreadStore.Get | p99 | 203ms | 149ms | -54ms | -26.63
| ThreadStore.GetTotalThreads | p99 | 181ms | 133ms | -48ms | -26.53
| ChannelStore.GetByName | p99 | 196ms | 144ms | -52ms | -26.51
| UserStore.GetByUsername | p99 | 276ms | 204ms | -72ms | -26.12
| UserStore.UpdateFailedPasswordAttempts | p99 | 130ms | 97ms | -33ms | -25.47
| PostPriorityStore.GetForPosts | p99 | 329ms | 246ms | -83ms | -25.26
| TeamStore.GetTeamsByUserId | p99 | 184ms | 138ms | -46ms | -25.04
| SystemStore.GetByName | p99 | 129ms | 97ms | -32ms | -24.84
| TeamStore.GetTeamsForUser | p99 | 182ms | 137ms | -45ms | -24.77
| PostPersistentNotificationStore.GetSingle | p99 | 182ms | 137ms | -45ms | -24.73
| GroupStore.GetByName | p99 | 143ms | 108ms | -35ms | -24.53
| PostAcknowledgementStore.GetForPosts | p99 | 326ms | 246ms | -80ms | -24.52
| TeamStore.GetMember | p99 | 122ms | 93ms | -29ms | -23.82
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 188ms | 144ms | -44ms | -23.46
| PostStore.Get | p99 | 399ms | 306ms | -93ms | -23.29
| TeamStore.GetAllPage | p99 | 186ms | 143ms | -43ms | -23.10
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 181ms | 140ms | -41ms | -22.62
| ThreadStore.GetThreadFollowers | p99 | 195ms | 151ms | -44ms | -22.57
| SessionStore.GetLRUSessions | p99 | 125ms | 97ms | -28ms | -22.49
| ChannelStore.GetMembersForUserWithPagination | p99 | 183ms | 143ms | -40ms | -21.86
| ThreadStore.GetTotalUnreadThreads | p99 | 179ms | 140ms | -39ms | -21.79
| UserStore.IsEmpty | p99 | 79ms | 62ms | -17ms | -21.49
| ChannelStore.GetChannelsByUser | p99 | 174ms | 137ms | -37ms | -21.27
| ChannelStore.Get | p99 | 308ms | 243ms | -65ms | -21.07
| SessionStore.UpdateLastActivityAt | p99 | 126ms | 100ms | -26ms | -20.60
| ThreadStore.GetThreadForUser | p99 | 302ms | 242ms | -60ms | -19.85
| PropertyFieldStore.SearchPropertyFields | p99 | 160ms | 129ms | -31ms | -19.41
| ChannelStore.IncrementMentionCount | p99 | 156ms | 126ms | -30ms | -19.27
| AuditStore.Save | p99 | 121ms | 98ms | -23ms | -19.06
| UserStore.GetForLogin | p99 | 165ms | 134ms | -31ms | -18.81
| PreferenceStore.Save | p99 | 382ms | 312ms | -70ms | -18.32
| UserStore.Update | p99 | 282ms | 233ms | -49ms | -17.40
| PreferenceStore.GetAll | p99 | 199ms | 165ms | -34ms | -17.09
| EmojiStore.GetByName | p99 | 207ms | 172ms | -35ms | -16.93
| ChannelStore.UpdateLastViewedAt | p99 | 136ms | 113ms | -23ms | -16.90
| ChannelStore.GetGuestCount | p99 | 207ms | 173ms | -34ms | -16.43
| ThreadStore.GetTotalUnreadMentions | p99 | 188ms | 158ms | -30ms | -15.95
| ChannelStore.Autocomplete | p99 | 287ms | 242ms | -45ms | -15.68
| TeamStore.Get | p99 | 198ms | 167ms | -31ms | -15.66
| ThreadStore.MarkAsRead | p99 | 122ms | 103ms | -19ms | -15.61
| StatusStore.Get | p99 | 212ms | 179ms | -33ms | -15.59
| PostStore.GetPostIdBeforeTime | p99 | 152ms | 129ms | -23ms | -15.16
| GroupStore.GetGroups | p99 | 206ms | 175ms | -31ms | -15.08
| UserStore.Get | p99 | 207ms | 177ms | -30ms | -14.53
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 147ms | 126ms | -21ms | -14.26
| ChannelStore.UpdateSidebarCategories | p99 | 1.847s | 1.585s | -262ms | -14.18
| ThreadStore.MaintainMembership | p99 | 282ms | 243ms | -39ms | -13.83
| PostStore.GetSingle | p99 | 203ms | 175ms | -28ms | -13.81
| DraftStore.Delete | p99 | 173ms | 150ms | -23ms | -13.32
| LinkMetadataStore.Get | p99 | 207ms | 180ms | -27ms | -13.07
| ChannelStore.CreateInitialSidebarCategories | p99 | 479ms | 419ms | -60ms | -12.52
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 202ms | 177ms | -25ms | -12.37
| PropertyValueStore.SearchPropertyValues | p99 | 229ms | 201ms | -28ms | -12.23
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 206ms | 181ms | -25ms | -12.12
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 191ms | 168ms | -23ms | -12.02
| ChannelStore.GetFileCount | p99 | 202ms | 178ms | -24ms | -11.86
| FileInfoStore.GetForPost | p99 | 228ms | 201ms | -27ms | -11.83
| ScheduledPostStore.CreateScheduledPost | p99 | 246ms | 217ms | -29ms | -11.79
| StatusStore.SaveOrUpdate | p99 | 186ms | 165ms | -21ms | -11.28
| ChannelStore.GetAllChannelMembersForUser | p99 | 200ms | 178ms | -22ms | -11.01
| ThreadStore.GetTeamsUnreadForUser | p99 | 228ms | 203ms | -25ms | -10.99
| ChannelStore.GetPinnedPostCount | p99 | 220ms | 196ms | -24ms | -10.91
| ChannelStore.GetMembersForUser | p99 | 225ms | 201ms | -24ms | -10.65
| PostStore.GetEtag | p99 | 225ms | 201ms | -24ms | -10.65
| ThreadStore.GetMembershipForUser | p99 | 212ms | 190ms | -22ms | -10.38
| PostStore.GetPosts | p99 | 107ms | 96ms | -11ms | -10.25
| ReactionStore.GetForPost | p99 | 168ms | 151ms | -17ms | -10.15
| DraftStore.GetDraftsForUser | p99 | 238ms | 214ms | -24ms | -10.08
| UserStore.GetProfileByIds | p99 | 224ms | 203ms | -21ms | -9.38
| UserStore.UpdateUpdateAt | p99 | 97ms | 88ms | -9ms | -9.32
| FileInfoStore.GetByIds | p99 | 226ms | 205ms | -21ms | -9.29
| ChannelStore.GetChannels | p99 | 230ms | 209ms | -21ms | -9.12
| UserStore.GetUnreadCount | p99 | 199ms | 181ms | -18ms | -9.04
| PostStore.GetPostsByThread | p99 | 214ms | 195ms | -19ms | -8.86
| JobStore.GetAllByStatus | p99 | 230ms | 210ms | -20ms | -8.70
| PreferenceStore.Get | p99 | 221ms | 202ms | -19ms | -8.60
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 93ms | 85ms | -8ms | -8.57
| SessionStore.Save | p99 | 223ms | 204ms | -19ms | -8.52
| PostStore.Save | p99 | 454ms | 416ms | -38ms | -8.37
| UserStore.Save | p99 | 800ms | 735ms | -65ms | -8.12
| ChannelStore.SearchGroupChannels | p99 | 235ms | 216ms | -19ms | -8.10
| ThreadStore.GetThreadsForUser | p99 | 235ms | 216ms | -19ms | -8.09
| ChannelStore.CreateDirectChannel | p99 | 826ms | 761ms | -65ms | -7.87
| BotStore.Get | p99 | 222ms | 205ms | -17ms | -7.65
| PostStore.GetPostIdAfterTime | p99 | 94ms | 87ms | -7ms | -7.43
| FileInfoStore.Get | p99 | 216ms | 200ms | -16ms | -7.42
| UserStore.GetProfilesByUsernames | p99 | 221ms | 205ms | -16ms | -7.23
| FileInfoStore.Save | p99 | 195ms | 181ms | -14ms | -7.18
| DraftStore.Get | p99 | 239ms | 222ms | -17ms | -7.12
| PostStore.GetPostsBefore | p99 | 226ms | 210ms | -16ms | -7.08
| ThreadStore.UpdateMembership | p99 | 105ms | 98ms | -7ms | -6.69
| UserStore.Count | p99 | 210ms | 196ms | -14ms | -6.67
| UserStore.AutocompleteUsersInChannel | p99 | 437ms | 408ms | -29ms | -6.63
| ThreadStore.GetThreadUnreadReplyCount | p99 | 228ms | 213ms | -15ms | -6.58
| TeamStore.SaveMember | p99 | 260ms | 243ms | -17ms | -6.53
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 239ms | 224ms | -15ms | -6.29
| StatusStore.GetByIds | p99 | 243ms | 228ms | -15ms | -6.17
| DraftStore.Upsert | p99 | 196ms | 184ms | -12ms | -6.11
| StatusStore.SaveOrUpdateMany | p99 | 218ms | 206ms | -12ms | -5.49
| PostStore.GetPostsAfter | p99 | 208ms | 197ms | -11ms | -5.30
| PostStore.SearchPostsForUser | p99 | 2.444s | 2.318s | -126ms | -5.16
| UserStore.GetAllProfilesInChannel | p99 | 2.271s | 2.156s | -115ms | -5.06
| WebhookStore.GetOutgoingByTeam | p99 | 238ms | 226ms | -12ms | -5.04
| SessionStore.Get | p99 | 241ms | 229ms | -12ms | -4.98
| ChannelStore.GetMemberForPost | p99 | 237ms | 226ms | -11ms | -4.65
| ChannelStore.GetMemberCount | p99 | 243ms | 232ms | -11ms | -4.53
| UserStore.UpdateLastLogin | p99 | 92ms | 88ms | -4ms | -4.34
| ProductNoticesStore.View | p99 | 994ms | 951ms | -43ms | -4.33
| PostStore.GetPostsSince | p99 | 243ms | 233ms | -10ms | -4.12
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 249ms | 239ms | -10ms | -4.02
| UserStore.Search | p99 | 249ms | 243ms | -6ms | -2.41
| TeamStore.GetTotalMemberCount | p99 | 242ms | 237ms | -5ms | -2.06
| TeamStore.GetActiveMemberCount | p99 | 242ms | 237ms | -5ms | -2.06
| FileInfoStore.AttachToPost | p99 | 225ms | 221ms | -4ms | -1.78
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 29ms | 198ms | 169ms | 576.71
| updateChannelBookmark | avg | 24ms | 27ms | 3ms | 12.60
| updateChannelBookmarkSortOrder | avg | 58ms | 65ms | 7ms | 12.15
| createChannel | avg | 446ms | 451ms | 5ms | 1.12
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 98ms | 965ms | 867ms | 889.23
| updateChannelBookmark | p99 | 50ms | 239ms | 189ms | 381.08
| autocompleteChannelsForTeamForSearch | p99 | 528ms | 720ms | 192ms | 36.34
| updateChannelBookmarkSortOrder | p99 | 243ms | 247ms | 4ms | 1.65
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | avg | 7ms | 0s | -7ms | -107.14
| getFilteredUsersStats | avg | 16ms | 0s | -16ms | -100.50
| getAnalytics | avg | 79ms | 0s | -79ms | -100.18
| getJobsByType | avg | 29ms | 0s | -29ms | -100.14
| channelMemberCountsByGroup | avg | 29ms | 0s | -29ms | -100.09
| getRolesByNames | avg | 21ms | 0s | -21ms | -100.01
| handleCheckCWSConnection | avg | 130ms | 0s | -130ms | -99.62
| getServerLimits | avg | 26ms | 0s | -26ms | -98.23
| getUserByUsername | avg | 2ms | 0s | -2ms | -89.79
| updateReadStateAllThreadsByUser | avg | 72ms | 8ms | -64ms | -88.34
| getChannelMembers | avg | 106ms | 27ms | -79ms | -74.68
| createChannelBookmark | avg | 114ms | 42ms | -72ms | -63.35
| followThreadByUser | avg | 118ms | 75ms | -43ms | -36.49
| setPostReminder | avg | 99ms | 74ms | -25ms | -25.19
| updateCategoriesForTeamForUser | avg | 249ms | 188ms | -61ms | -24.47
| unfollowThreadByUser | avg | 75ms | 57ms | -18ms | -24.09
| logout | avg | 150ms | 119ms | -31ms | -20.69
| listCPAValues | avg | 21ms | 17ms | -4ms | -19.30
| patchPost | avg | 126ms | 103ms | -23ms | -18.23
| searchGroupChannels | avg | 23ms | 19ms | -4ms | -17.06
| getUser | avg | 24ms | 20ms | -4ms | -16.58
| getDrafts | avg | 24ms | 20ms | -4ms | -16.54
| getTeamsUnreadForUser | avg | 25ms | 21ms | -4ms | -16.11
| getChannelsForUser | avg | 13ms | 11ms | -2ms | -15.84
| updatePreferences | avg | 51ms | 43ms | -8ms | -15.80
| addChannelMember | avg | 588ms | 498ms | -90ms | -15.32
| createDirectChannel | avg | 629ms | 533ms | -96ms | -15.27
| getTeamsForUser | avg | 13ms | 11ms | -2ms | -15.15
| getClientConfig | avg | 27ms | 23ms | -4ms | -15.03
| getChannelsForTeamForUser | avg | 20ms | 17ms | -3ms | -14.95
| getTeamMember | avg | 14ms | 12ms | -2ms | -14.23
| getTeamMembersForUser | avg | 14ms | 12ms | -2ms | -14.13
| getChannelMembersForUser | avg | 14ms | 12ms | -2ms | -14.07
| getUsers | avg | 21ms | 18ms | -3ms | -14.07
| getChannel | avg | 36ms | 31ms | -5ms | -13.93
| getThreadsForUser | avg | 22ms | 19ms | -3ms | -13.38
| getAllTeams | avg | 15ms | 13ms | -2ms | -13.34
| getPreferences | avg | 15ms | 13ms | -2ms | -13.32
| getTeamScheduledPosts | avg | 23ms | 20ms | -3ms | -13.06
| deleteDraft | avg | 23ms | 20ms | -3ms | -12.95
| saveReaction | avg | 55ms | 48ms | -7ms | -12.62
| getPostsForChannel | avg | 167ms | 146ms | -21ms | -12.55
| getPostsForChannelAroundLastUnread | avg | 65ms | 57ms | -8ms | -12.31
| addTeamMember | avg | 1.624s | 1.43s | -194ms | -11.95
| getChannelMember | avg | 25ms | 22ms | -3ms | -11.90
| viewChannel | avg | 64ms | 57ms | -7ms | -10.91
| getPostThread | avg | 92ms | 82ms | -10ms | -10.85
| getUsersByNames | avg | 19ms | 17ms | -2ms | -10.48
| getChannelMembersForTeamForUser | avg | 19ms | 17ms | -2ms | -10.35
| searchPostsInTeam | avg | 242ms | 218ms | -24ms | -9.93
| deletePost | avg | 106ms | 96ms | -10ms | -9.39
| updateReadStateThreadByUser | avg | 185ms | 169ms | -16ms | -8.66
| getPublicChannelsForTeam | avg | 35ms | 32ms | -3ms | -8.66
| getCategoriesForTeamForUser | avg | 23ms | 21ms | -2ms | -8.56
| upsertDraft | avg | 23ms | 21ms | -2ms | -8.56
| getTeamStats | avg | 84ms | 77ms | -7ms | -8.29
| createUser | avg | 460ms | 423ms | -37ms | -8.05
| createPost | avg | 824ms | 759ms | -65ms | -7.89
| deleteChannelBookmark | avg | 28ms | 26ms | -2ms | -7.06
| searchUsers | avg | 58ms | 54ms | -4ms | -6.94
| searchAllChannels | avg | 58ms | 54ms | -4ms | -6.88
| autocompleteUsers | avg | 77ms | 72ms | -5ms | -6.49
| createGroupChannel | avg | 1.033s | 969ms | -64ms | -6.20
| autocompleteChannelsForTeamForSearch | avg | 85ms | 80ms | -5ms | -5.86
| getFileThumbnail | avg | 70ms | 66ms | -4ms | -5.75
| getFilePreview | avg | 81ms | 77ms | -4ms | -4.95
| getProfileImage | avg | 81ms | 77ms | -4ms | -4.95
| login | avg | 247ms | 235ms | -12ms | -4.86
| removeUserCustomStatus | avg | 365ms | 354ms | -11ms | -3.01
| uploadFileStream | avg | 569ms | 561ms | -8ms | -1.41
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 25ms | 0s | -25ms | -101.83
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getUserByUsername | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| getServerLimits | p99 | 50ms | 0s | -50ms | -100.50
| getAnalytics | p99 | 100ms | 0s | -100ms | -100.47
| handleCheckCWSConnection | p99 | 247ms | 0s | -247ms | -100.00
| channelMemberCountsByGroup | p99 | 97ms | 0s | -97ms | -99.74
| getRolesByNames | p99 | 49ms | 0s | -49ms | -99.49
| getJobsByType | p99 | 97ms | 0s | -97ms | -99.49
| getChannelMembers | p99 | 940ms | 98ms | -842ms | -89.57
| updateReadStateAllThreadsByUser | p99 | 243ms | 48ms | -195ms | -80.16
| createChannelBookmark | p99 | 895ms | 237ms | -658ms | -73.52
| setPostReminder | p99 | 858ms | 460ms | -398ms | -46.41
| followThreadByUser | p99 | 725ms | 422ms | -303ms | -41.79
| createSchedulePost | p99 | 365ms | 231ms | -134ms | -36.71
| getChannel | p99 | 408ms | 276ms | -132ms | -32.35
| getPostsForChannelAroundLastUnread | p99 | 734ms | 497ms | -237ms | -32.31
| logout | p99 | 690ms | 476ms | -214ms | -31.02
| getUser | p99 | 366ms | 259ms | -107ms | -29.27
| getUserStatusesByIds | p99 | 138ms | 98ms | -40ms | -29.03
| addChannelMember | p99 | 3.486s | 2.487s | -999ms | -28.66
| updateCategoriesForTeamForUser | p99 | 2.85s | 2.043s | -807ms | -28.32
| getUsers | p99 | 343ms | 249ms | -94ms | -27.38
| patchPost | p99 | 1.1s | 812ms | -288ms | -26.18
| createDirectChannel | p99 | 3.222s | 2.385s | -837ms | -25.98
| viewChannel | p99 | 724ms | 545ms | -179ms | -24.72
| getChannelMember | p99 | 319ms | 242ms | -77ms | -24.16
| unfollowThreadByUser | p99 | 639ms | 488ms | -151ms | -23.64
| searchAllChannels | p99 | 322ms | 246ms | -76ms | -23.60
| createGroupChannel | p99 | 6.25s | 4.8s | -1.45s | -23.20
| getClientConfig | p99 | 330ms | 255ms | -75ms | -22.74
| getTeamsForUser | p99 | 190ms | 149ms | -41ms | -21.53
| getChannelMembersForUser | p99 | 189ms | 150ms | -39ms | -20.63
| updateReadStateThreadByUser | p99 | 1.852s | 1.501s | -351ms | -18.95
| getChannelsForUser | p99 | 182ms | 148ms | -34ms | -18.72
| getUsersByIds | p99 | 73ms | 61ms | -12ms | -16.52
| getTeamsUnreadForUser | p99 | 285ms | 238ms | -47ms | -16.46
| getTeamMember | p99 | 191ms | 161ms | -30ms | -15.67
| getPreferences | p99 | 207ms | 176ms | -31ms | -14.99
| getPostThread | p99 | 917ms | 785ms | -132ms | -14.40
| getTeamMembersForUser | p99 | 204ms | 175ms | -29ms | -14.22
| searchUsers | p99 | 282ms | 246ms | -36ms | -12.78
| getAllTeams | p99 | 212ms | 185ms | -27ms | -12.74
| getPostsForChannel | p99 | 2.23s | 1.991s | -239ms | -10.72
| listCPAValues | p99 | 234ms | 209ms | -25ms | -10.70
| addTeamMember | p99 | 9.763s | 8.73s | -1.033s | -10.58
| getChannelMembersForTeamForUser | p99 | 229ms | 206ms | -23ms | -10.05
| searchGroupChannels | p99 | 241ms | 218ms | -23ms | -9.55
| saveReaction | p99 | 499ms | 453ms | -46ms | -9.22
| listCPAFields | p99 | 198ms | 181ms | -17ms | -8.61
| listChannelBookmarksForChannel | p99 | 214ms | 196ms | -18ms | -8.40
| getChannelsForTeamForUser | p99 | 234ms | 215ms | -19ms | -8.12
| getTeamScheduledPosts | p99 | 246ms | 226ms | -20ms | -8.12
| getDrafts | p99 | 249ms | 229ms | -20ms | -8.04
| createChannel | p99 | 2.305s | 2.125s | -180ms | -7.81
| getThreadsForUser | p99 | 241ms | 224ms | -17ms | -7.06
| getUsersByNames | p99 | 227ms | 212ms | -15ms | -6.61
| updatePreferences | p99 | 467ms | 437ms | -30ms | -6.43
| deleteDraft | p99 | 245ms | 230ms | -15ms | -6.12
| autocompleteUsers | p99 | 450ms | 423ms | -27ms | -6.00
| getCategoriesForTeamForUser | p99 | 244ms | 230ms | -14ms | -5.74
| getFileThumbnail | p99 | 446ms | 421ms | -25ms | -5.61
| upsertDraft | p99 | 239ms | 226ms | -13ms | -5.44
| getChannelStats | p99 | 193ms | 183ms | -10ms | -5.18
| createPost | p99 | 4.929s | 4.678s | -251ms | -5.09
| searchPostsInTeam | p99 | 2.456s | 2.344s | -112ms | -4.56
| getFilePreview | p99 | 475ms | 456ms | -19ms | -4.00
| getChannelUnread | p99 | 239ms | 231ms | -8ms | -3.35
| createUser | p99 | 2.415s | 2.343s | -72ms | -2.98
| getProfileImage | p99 | 491ms | 479ms | -12ms | -2.44
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 11ms| 10ms | -1ms | -9.093
| |  P99| 121ms| 98ms | -23ms | -19.055
| BotStore.Get |  Avg| 15ms| 13ms | -2ms | -13.771
| |  P99| 222ms| 205ms | -17ms | -7.649
| BotStore.GetAll |  Avg| 36ms| 0s | -36ms | -101.194
| |  P99| 244ms| 0s | -244ms | -100.001
| ChannelBookmarkStore.Delete |  Avg| 18ms| 12ms | -6ms | -33.902
| |  P99| 238ms| 49ms | -189ms | -79.412
| ChannelBookmarkStore.Get |  Avg| 13ms| 9ms | -4ms | -30.005
| |  P99| 225ms| 48ms | -177ms | -78.842
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 13ms| 12ms | -1ms | -7.537
| |  P99| 191ms| 168ms | -23ms | -12.022
| ChannelBookmarkStore.Save |  Avg| 67ms| 32ms | -35ms | -52.282
| |  P99| 865ms| 234ms | -631ms | -72.949
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 26ms| 59ms | 33ms | 125.346
| |  P99| 239ms| 245ms | 6ms | 2.505
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring |  Avg| 44ms| 0s | -44ms | -100.378
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 163ms| 67ms | -96ms | -58.863
| |  P99| 249ms| 239ms | -10ms | -4.022
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 9ms| 8ms | -1ms | -11.540
| |  P99| 93ms| 85ms | -8ms | -8.567
| ChannelStore.AnalyticsCountAll |  Avg| 22ms| 0s | -22ms | -98.703
| |  P99| 25ms| 0s | -25ms | -100.562
| ChannelStore.Autocomplete |  Avg| 57ms| 53ms | -4ms | -7.059
| |  P99| 287ms| 242ms | -45ms | -15.682
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 84ms| 80ms | -4ms | -4.734
| |  P99| 492ms| 720ms | 228ms | 46.295
| ChannelStore.CreateDirectChannel |  Avg| 98ms| 83ms | -15ms | -15.372
| |  P99| 826ms| 761ms | -65ms | -7.869
| ChannelStore.CreateInitialSidebarCategories |  Avg| 43ms| 36ms | -7ms | -16.442
| |  P99| 479ms| 419ms | -60ms | -12.517
| ChannelStore.CreateSidebarCategory |  Avg| 19ms| 172ms | 153ms | 786.047
| |  P99| 49ms| 494ms | 445ms | 912.820
| ChannelStore.Get |  Avg| 29ms| 25ms | -4ms | -13.854
| |  P99| 308ms| 243ms | -65ms | -21.070
| ChannelStore.GetAllChannelMembersForUser |  Avg| 17ms| 15ms | -2ms | -11.941
| |  P99| 200ms| 178ms | -22ms | -11.006
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 458ms| 484ms | 26ms | 5.673
| ChannelStore.GetByName |  Avg| 16ms| 14ms | -2ms | -12.287
| |  P99| 196ms| 144ms | -52ms | -26.509
| ChannelStore.GetChannelUnread |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 224ms| 222ms | -2ms | -0.893
| ChannelStore.GetChannels |  Avg| 19ms| 17ms | -2ms | -10.266
| |  P99| 230ms| 209ms | -21ms | -9.123
| ChannelStore.GetChannelsByUser |  Avg| 12ms| 11ms | -1ms | -8.181
| |  P99| 174ms| 137ms | -37ms | -21.267
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 15ms| 13ms | -2ms | -13.256
| |  P99| 206ms| 181ms | -25ms | -12.122
| ChannelStore.GetFileCount |  Avg| 16ms| 14ms | -2ms | -12.264
| |  P99| 202ms| 178ms | -24ms | -11.857
| ChannelStore.GetGuestCount |  Avg| 16ms| 14ms | -2ms | -12.177
| |  P99| 207ms| 173ms | -34ms | -16.429
| ChannelStore.GetMany |  Avg| 3ms| 0s | -3ms | -113.446
| |  P99| 5ms| 0s | -5ms | -100.921
| ChannelStore.GetMember |  Avg| 11ms| 9ms | -2ms | -17.822
| |  P99| 155ms| 109ms | -46ms | -29.662
| ChannelStore.GetMemberCount |  Avg| 43ms| 39ms | -4ms | -9.404
| |  P99| 243ms| 232ms | -11ms | -4.526
| ChannelStore.GetMemberCountsByGroup |  Avg| 27ms| 0s | -27ms | -101.766
| |  P99| 97ms| 0s | -97ms | -100.000
| ChannelStore.GetMemberForPost |  Avg| 24ms| 21ms | -3ms | -12.687
| |  P99| 237ms| 226ms | -11ms | -4.647
| ChannelStore.GetMemberLastViewedAt |  Avg| 10ms| 9ms | -1ms | -9.598
| |  P99| 145ms| 100ms | -45ms | -31.111
| ChannelStore.GetMembers |  Avg| 66ms| 26ms | -40ms | -60.186
| |  P99| 470ms| 98ms | -372ms | -79.150
| ChannelStore.GetMembersForUser |  Avg| 19ms| 16ms | -3ms | -15.916
| |  P99| 225ms| 201ms | -24ms | -10.647
| ChannelStore.GetMembersForUserWithPagination |  Avg| 14ms| 12ms | -2ms | -14.423
| |  P99| 183ms| 143ms | -40ms | -21.863
| ChannelStore.GetPinnedPostCount |  Avg| 16ms| 14ms | -2ms | -12.371
| |  P99| 220ms| 196ms | -24ms | -10.913
| ChannelStore.GetPublicChannelsForTeam |  Avg| 32ms| 31ms | -1ms | -3.114
| |  P99| 215ms| 233ms | 18ms | 8.375
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 22ms| 20ms | -2ms | -8.972
| |  P99| 239ms| 224ms | -15ms | -6.286
| ChannelStore.GetSidebarCategory |  Avg| 45ms| 25ms | -20ms | -44.567
| |  P99| 830ms| 242ms | -588ms | -70.845
| ChannelStore.GetTeamChannels |  Avg| 36ms| 54ms | 18ms | 49.807
| |  P99| 230ms| 438ms | 208ms | 90.239
| ChannelStore.IncrementMentionCount |  Avg| 11ms| 9ms | -2ms | -18.669
| |  P99| 156ms| 126ms | -30ms | -19.272
| ChannelStore.Save |  Avg| 53ms| 51ms | -2ms | -3.786
| |  P99| 443ms| 615ms | 172ms | 38.826
| ChannelStore.SaveMember |  Avg| 81ms| 70ms | -11ms | -13.619
| |  P99| 815ms| 541ms | -274ms | -33.613
| ChannelStore.SearchGroupChannels |  Avg| 23ms| 19ms | -4ms | -17.771
| |  P99| 235ms| 216ms | -19ms | -8.096
| ChannelStore.UpdateLastViewedAt |  Avg| 13ms| 12ms | -1ms | -7.933
| |  P99| 136ms| 113ms | -23ms | -16.901
| ChannelStore.UpdateSidebarCategories |  Avg| 139ms| 124ms | -15ms | -10.826
| |  P99| 1.847s| 1.585s | -262ms | -14.182
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 10ms| 9ms | -1ms | -9.815
| |  P99| 147ms| 126ms | -21ms | -14.262
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 18ms| 17ms | -1ms | -5.699
| |  P99| 169ms| 193ms | 24ms | 14.201
| CommandWebhookStore.Cleanup |  Avg| 1ms| 16ms | 15ms | 1014.533
| |  P99| 5ms| 98ms | 93ms | 1878.748
| ComplianceStore.MessageExport |  Avg| 8ms| 556ms | 548ms | 6981.750
| |  P99| 25ms| 2.396s | 2.371s | 9599.190
| DesktopTokensStore.DeleteOlderThan |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Delete |  Avg| 15ms| 13ms | -2ms | -13.434
| |  P99| 173ms| 150ms | -23ms | -13.325
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 13ms| 21ms | 8ms | 61.103
| |  P99| 85ms| 96ms | 11ms | 12.941
| DraftStore.Get |  Avg| 22ms| 19ms | -3ms | -13.804
| |  P99| 239ms| 222ms | -17ms | -7.123
| DraftStore.GetDraftsForUser |  Avg| 22ms| 19ms | -3ms | -13.517
| |  P99| 238ms| 214ms | -24ms | -10.083
| DraftStore.Upsert |  Avg| 17ms| 16ms | -1ms | -5.881
| |  P99| 196ms| 184ms | -12ms | -6.113
| EmojiStore.GetByName |  Avg| 15ms| 12ms | -3ms | -20.628
| |  P99| 207ms| 172ms | -35ms | -16.930
| EmojiStore.GetMultipleByName |  Avg| 23ms| 20ms | -3ms | -13.115
| |  P99| 229ms| 98ms | -131ms | -57.205
| FileInfoStore.AttachToPost |  Avg| 21ms| 20ms | -1ms | -4.686
| |  P99| 225ms| 221ms | -4ms | -1.777
| FileInfoStore.Get |  Avg| 16ms| 15ms | -1ms | -6.117
| |  P99| 216ms| 200ms | -16ms | -7.420
| FileInfoStore.GetByIds |  Avg| 17ms| 15ms | -2ms | -12.097
| |  P99| 226ms| 205ms | -21ms | -9.292
| FileInfoStore.GetForPost |  Avg| 16ms| 14ms | -2ms | -12.158
| |  P99| 228ms| 201ms | -27ms | -11.835
| FileInfoStore.Save |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 195ms| 181ms | -14ms | -7.185
| FileInfoStore.SetContent |  Avg| 26ms| 27ms | 1ms | 3.897
| |  P99| 238ms| 272ms | 34ms | 14.266
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 10ms| 9ms | -1ms | -9.662
| |  P99| 146ms| 95ms | -51ms | -34.821
| GroupStore.GetByName |  Avg| 11ms| 10ms | -1ms | -8.984
| |  P99| 143ms| 108ms | -35ms | -24.531
| GroupStore.GetGroups |  Avg| 15ms| 13ms | -2ms | -13.391
| |  P99| 206ms| 175ms | -31ms | -15.082
| JobStore.GetAllByStatus |  Avg| 21ms| 17ms | -4ms | -19.419
| |  P99| 230ms| 210ms | -20ms | -8.700
| JobStore.GetAllByTypePage |  Avg| 29ms| 0s | -29ms | -100.844
| |  P99| 97ms| 0s | -97ms | -99.488
| JobStore.GetAllByTypesAndStatusesPage |  Avg| 2ms| 0s | -2ms | -100.582
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 24ms| 17ms | -7ms | -29.576
| |  P99| 216ms| 224ms | 8ms | 3.707
| JobStore.GetNewestJobByStatusesAndType |  Avg| 19ms| 11ms | -8ms | -41.090
| |  P99| 233ms| 123ms | -110ms | -47.261
| JobStore.Save |  Avg| 16ms| 15ms | -1ms | -6.334
| |  P99| 175ms| 125ms | -50ms | -28.571
| JobStore.UpdateOptimistically |  Avg| 10ms| 9ms | -1ms | -10.009
| |  P99| 89ms| 189ms | 100ms | 111.856
| JobStore.UpdateStatus |  Avg| 8ms| 11ms | 3ms | 38.063
| |  P99| 75ms| 210ms | 135ms | 179.986
| JobStore.UpdateStatusOptimistically |  Avg| 10ms| 13ms | 3ms | 29.973
| |  P99| 90ms| 190ms | 100ms | 111.107
| LicenseStore.GetAll |  Avg| 5ms| 0s | -5ms | -98.380
| |  P99| 24ms| 0s | -24ms | -98.361
| LinkMetadataStore.Get |  Avg| 14ms| 12ms | -2ms | -14.204
| |  P99| 207ms| 180ms | -27ms | -13.068
| LinkMetadataStore.Save |  Avg| 14ms| 8ms | -6ms | -43.177
| |  P99| 178ms| 80ms | -98ms | -55.058
| PluginStore.Delete |  Avg| 35ms| 0s | -35ms | -100.081
| |  P99| 98ms| 0s | -98ms | -100.000
| PluginStore.List |  Avg| 14ms| 16ms | 2ms | 13.821
| |  P99| 193ms| 350ms | 157ms | 81.347
| PluginStore.SetWithOptions |  Avg| 90ms| 0s | -90ms | -100.349
| |  P99| 247ms| 0s | -247ms | -100.000
| PostAcknowledgementStore.GetForPost |  Avg| 12ms| 9ms | -3ms | -24.168
| |  P99| 189ms| 92ms | -97ms | -51.322
| PostAcknowledgementStore.GetForPosts |  Avg| 22ms| 19ms | -3ms | -13.749
| |  P99| 326ms| 246ms | -80ms | -24.516
| PostPersistentNotificationStore.DeleteExpired |  Avg| 8ms| 9ms | 1ms | 12.931
| |  P99| 160ms| 178ms | 18ms | 11.251
| PostPersistentNotificationStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 70ms| 88ms | 18ms | 25.716
| PostPersistentNotificationStore.GetSingle |  Avg| 11ms| 10ms | -1ms | -8.698
| |  P99| 182ms| 137ms | -45ms | -24.734
| PostPriorityStore.GetForPost |  Avg| 12ms| 9ms | -3ms | -25.785
| |  P99| 156ms| 96ms | -60ms | -38.461
| PostPriorityStore.GetForPosts |  Avg| 23ms| 19ms | -4ms | -17.716
| |  P99| 329ms| 246ms | -83ms | -25.262
| PostStore.AnalyticsPostCount |  Avg| 273ms| 198ms | -75ms | -27.435
| |  P99| 980ms| 496ms | -484ms | -49.387
| PostStore.AnalyticsPostCountByTeam |  Avg| 3ms| 0s | -3ms | -115.826
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.Delete |  Avg| 59ms| 60ms | 1ms | 1.695
| |  P99| 425ms| 443ms | 18ms | 4.235
| PostStore.Get |  Avg| 38ms| 33ms | -5ms | -13.102
| |  P99| 399ms| 306ms | -93ms | -23.288
| PostStore.GetEtag |  Avg| 18ms| 16ms | -2ms | -10.859
| |  P99| 225ms| 201ms | -24ms | -10.645
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 7ms| 6ms | -1ms | -14.238
| |  P99| 94ms| 87ms | -7ms | -7.430
| PostStore.GetPostIdBeforeTime |  Avg| 11ms| 10ms | -1ms | -9.083
| |  P99| 152ms| 129ms | -23ms | -15.162
| PostStore.GetPostReminderMetadata |  Avg| 13ms| 19ms | 6ms | 45.604
| |  P99| 92ms| 218ms | 126ms | 136.744
| PostStore.GetPostReminders |  Avg| 30ms| 31ms | 1ms | 3.387
| |  P99| 407ms| 425ms | 18ms | 4.417
| PostStore.GetPosts |  Avg| 11ms| 10ms | -1ms | -9.436
| |  P99| 107ms| 96ms | -11ms | -10.247
| PostStore.GetPostsAfter |  Avg| 16ms| 14ms | -2ms | -12.575
| |  P99| 208ms| 197ms | -11ms | -5.297
| PostStore.GetPostsBefore |  Avg| 20ms| 18ms | -2ms | -10.138
| |  P99| 226ms| 210ms | -16ms | -7.083
| PostStore.GetPostsByThread |  Avg| 22ms| 21ms | -1ms | -4.585
| |  P99| 214ms| 195ms | -19ms | -8.863
| PostStore.GetPostsSince |  Avg| 33ms| 30ms | -3ms | -9.139
| |  P99| 243ms| 233ms | -10ms | -4.121
| PostStore.GetSingle |  Avg| 14ms| 12ms | -2ms | -14.614
| |  P99| 203ms| 175ms | -28ms | -13.810
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 45ms| 39ms | -6ms | -13.438
| |  P99| 454ms| 416ms | -38ms | -8.367
| PostStore.SearchPostsForUser |  Avg| 208ms| 187ms | -21ms | -10.112
| |  P99| 2.444s| 2.318s | -126ms | -5.156
| PostStore.SetPostReminder |  Avg| 36ms| 23ms | -13ms | -36.233
| |  P99| 357ms| 202ms | -155ms | -43.358
| PostStore.Update |  Avg| 36ms| 29ms | -7ms | -19.300
| |  P99| 245ms| 248ms | 3ms | 1.222
| PreferenceStore.DeleteCategoryAndName |  Avg| 12ms| 17ms | 5ms | 43.348
| |  P99| 92ms| 96ms | 4ms | 4.324
| PreferenceStore.Get |  Avg| 17ms| 15ms | -2ms | -11.440
| |  P99| 221ms| 202ms | -19ms | -8.596
| PreferenceStore.GetAll |  Avg| 14ms| 12ms | -2ms | -13.973
| |  P99| 199ms| 165ms | -34ms | -17.094
| PreferenceStore.Save |  Avg| 34ms| 29ms | -5ms | -14.525
| |  P99| 382ms| 312ms | -70ms | -18.322
| ProductNoticesStore.ClearOldNotices |  Avg| 43ms| 37ms | -6ms | -14.047
| |  P99| 99ms| 50ms | -49ms | -49.495
| ProductNoticesStore.View |  Avg| 111ms| 98ms | -13ms | -11.694
| |  P99| 994ms| 951ms | -43ms | -4.328
| PropertyFieldStore.SearchPropertyFields |  Avg| 11ms| 10ms | -1ms | -8.768
| |  P99| 160ms| 129ms | -31ms | -19.405
| PropertyValueStore.SearchPropertyValues |  Avg| 19ms| 16ms | -3ms | -15.584
| |  P99| 229ms| 201ms | -28ms | -12.229
| ReactionStore.GetForPost |  Avg| 14ms| 12ms | -2ms | -14.693
| |  P99| 168ms| 151ms | -17ms | -10.147
| RetentionPolicyStore.GetAll |  Avg| 29ms| 0s | -29ms | -98.993
| |  P99| 50ms| 0s | -50ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 34ms| 0s | -34ms | -98.952
| |  P99| 99ms| 0s | -99ms | -100.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 38ms| 13ms | -25ms | -66.165
| |  P99| 415ms| 85ms | -330ms | -79.595
| RoleStore.GetByNames |  Avg| 52ms| 27ms | -25ms | -47.853
| |  P99| 479ms| 198ms | -281ms | -58.680
| ScheduledPostStore.CreateScheduledPost |  Avg| 18ms| 19ms | 1ms | 5.576
| |  P99| 246ms| 217ms | -29ms | -11.788
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 25ms| 35ms | 10ms | 40.230
| |  P99| 232ms| 425ms | 193ms | 83.369
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 11ms| 10ms | -1ms | -8.886
| |  P99| 164ms| 105ms | -59ms | -36.044
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 15ms| 13ms | -2ms | -12.919
| |  P99| 94ms| 93ms | -1ms | -1.066
| SessionStore.Get |  Avg| 24ms| 21ms | -3ms | -12.649
| |  P99| 241ms| 229ms | -12ms | -4.977
| SessionStore.GetLRUSessions |  Avg| 10ms| 9ms | -1ms | -9.995
| |  P99| 125ms| 97ms | -28ms | -22.489
| SessionStore.GetSessionsExpired |  Avg| 16ms| 5ms | -11ms | -66.695
| |  P99| 96ms| 23ms | -73ms | -75.844
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 13ms| 12ms | -1ms | -7.696
| |  P99| 202ms| 177ms | -25ms | -12.374
| SessionStore.Remove |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 69ms| 92ms | 23ms | 33.333
| SessionStore.Save |  Avg| 19ms| 17ms | -2ms | -10.478
| |  P99| 223ms| 204ms | -19ms | -8.518
| SessionStore.UpdateLastActivityAt |  Avg| 12ms| 11ms | -1ms | -8.455
| |  P99| 126ms| 100ms | -26ms | -20.603
| StatusStore.Get |  Avg| 15ms| 13ms | -2ms | -12.985
| |  P99| 212ms| 179ms | -33ms | -15.592
| StatusStore.GetByIds |  Avg| 24ms| 21ms | -3ms | -12.440
| |  P99| 243ms| 228ms | -15ms | -6.168
| StatusStore.SaveOrUpdate |  Avg| 15ms| 13ms | -2ms | -13.339
| |  P99| 186ms| 165ms | -21ms | -11.283
| StatusStore.SaveOrUpdateMany |  Avg| 20ms| 18ms | -2ms | -10.065
| |  P99| 218ms| 206ms | -12ms | -5.495
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 17ms| 19ms | 2ms | 11.608
| |  P99| 202ms| 221ms | 19ms | 9.383
| StatusStore.UpdateLastActivityAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 112ms| 114ms | 2ms | 1.788
| SystemStore.GetByName |  Avg| 9ms| 8ms | -1ms | -11.365
| |  P99| 129ms| 97ms | -32ms | -24.835
| TeamStore.AnalyticsTeamCount |  Avg| 3ms| 0s | -3ms | -108.271
| |  P99| 5ms| 0s | -5ms | -100.940
| TeamStore.Get |  Avg| 13ms| 11ms | -2ms | -15.359
| |  P99| 198ms| 167ms | -31ms | -15.658
| TeamStore.GetActiveMemberCount |  Avg| 75ms| 70ms | -5ms | -6.638
| |  P99| 242ms| 237ms | -5ms | -2.064
| TeamStore.GetAllPage |  Avg| 13ms| 11ms | -2ms | -15.694
| |  P99| 186ms| 143ms | -43ms | -23.102
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 13ms| 11ms | -2ms | -15.127
| |  P99| 188ms| 144ms | -44ms | -23.460
| TeamStore.GetMember |  Avg| 9ms| 8ms | -1ms | -10.848
| |  P99| 122ms| 93ms | -29ms | -23.820
| TeamStore.GetTeamsByUserId |  Avg| 13ms| 11ms | -2ms | -15.667
| |  P99| 184ms| 138ms | -46ms | -25.044
| TeamStore.GetTeamsForUser |  Avg| 13ms| 11ms | -2ms | -15.928
| |  P99| 182ms| 137ms | -45ms | -24.765
| TeamStore.GetTotalMemberCount |  Avg| 70ms| 60ms | -10ms | -14.234
| |  P99| 242ms| 237ms | -5ms | -2.064
| TeamStore.SaveMember |  Avg| 41ms| 37ms | -4ms | -9.724
| |  P99| 260ms| 243ms | -17ms | -6.528
| ThreadStore.Get |  Avg| 14ms| 12ms | -2ms | -14.125
| |  P99| 203ms| 149ms | -54ms | -26.625
| ThreadStore.GetMembershipForUser |  Avg| 15ms| 13ms | -2ms | -13.151
| |  P99| 212ms| 190ms | -22ms | -10.381
| ThreadStore.GetTeamsUnreadForUser |  Avg| 18ms| 15ms | -3ms | -16.963
| |  P99| 228ms| 203ms | -25ms | -10.987
| ThreadStore.GetThreadFollowers |  Avg| 13ms| 11ms | -2ms | -15.109
| |  P99| 195ms| 151ms | -44ms | -22.570
| ThreadStore.GetThreadForUser |  Avg| 26ms| 24ms | -2ms | -7.606
| |  P99| 302ms| 242ms | -60ms | -19.852
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 26ms| 24ms | -2ms | -7.832
| |  P99| 228ms| 213ms | -15ms | -6.579
| ThreadStore.GetThreadsForUser |  Avg| 22ms| 19ms | -3ms | -13.700
| |  P99| 235ms| 216ms | -19ms | -8.093
| ThreadStore.GetTotalThreads |  Avg| 13ms| 11ms | -2ms | -15.779
| |  P99| 181ms| 133ms | -48ms | -26.535
| ThreadStore.GetTotalUnreadMentions |  Avg| 13ms| 12ms | -1ms | -7.571
| |  P99| 188ms| 158ms | -30ms | -15.947
| ThreadStore.GetTotalUnreadThreads |  Avg| 13ms| 11ms | -2ms | -15.815
| |  P99| 179ms| 140ms | -39ms | -21.789
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 13ms| 11ms | -2ms | -15.417
| |  P99| 181ms| 140ms | -41ms | -22.623
| ThreadStore.MaintainMembership |  Avg| 24ms| 21ms | -3ms | -12.571
| |  P99| 282ms| 243ms | -39ms | -13.830
| ThreadStore.MarkAllAsReadByChannels |  Avg| 12ms| 11ms | -1ms | -8.241
| |  P99| 150ms| 100ms | -50ms | -33.223
| ThreadStore.MarkAllAsReadByTeam |  Avg| 72ms| 8ms | -64ms | -88.499
| |  P99| 243ms| 48ms | -195ms | -80.164
| ThreadStore.MarkAsRead |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 122ms| 103ms | -19ms | -15.613
| ThreadStore.UpdateMembership |  Avg| 11ms| 10ms | -1ms | -9.147
| |  P99| 105ms| 98ms | -7ms | -6.693
| TokenStore.Cleanup |  Avg| 2ms| 14ms | 12ms | 641.722
| |  P99| 10ms| 98ms | 88ms | 907.193
| UserAccessTokenStore.GetByToken |  Avg| 17ms| 12ms | -5ms | -29.966
| |  P99| 219ms| 94ms | -125ms | -56.948
| UserStore.AnalyticsActiveCount |  Avg| 24ms| 0s | -24ms | -99.584
| |  P99| 25ms| 0s | -25ms | -100.562
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 12ms| 0s | -12ms | -104.242
| |  P99| 25ms| 0s | -25ms | -100.604
| UserStore.AutocompleteUsersInChannel |  Avg| 81ms| 77ms | -4ms | -4.914
| |  P99| 437ms| 408ms | -29ms | -6.632
| UserStore.Count |  Avg| 28ms| 26ms | -2ms | -7.216
| |  P99| 210ms| 196ms | -14ms | -6.668
| UserStore.Get |  Avg| 15ms| 12ms | -3ms | -20.430
| |  P99| 207ms| 177ms | -30ms | -14.528
| UserStore.GetAllProfiles |  Avg| 11ms| 9ms | -2ms | -18.942
| |  P99| 133ms| 95ms | -38ms | -28.595
| UserStore.GetAllProfilesInChannel |  Avg| 418ms| 380ms | -38ms | -9.097
| |  P99| 2.271s| 2.156s | -115ms | -5.063
| UserStore.GetByUsername |  Avg| 20ms| 16ms | -4ms | -19.665
| |  P99| 276ms| 204ms | -72ms | -26.123
| UserStore.GetForLogin |  Avg| 12ms| 11ms | -1ms | -8.275
| |  P99| 165ms| 134ms | -31ms | -18.812
| UserStore.GetMany |  Avg| 20ms| 8ms | -12ms | -61.370
| |  P99| 216ms| 85ms | -131ms | -60.704
| UserStore.GetProfileByIds |  Avg| 18ms| 15ms | -3ms | -16.788
| |  P99| 224ms| 203ms | -21ms | -9.379
| UserStore.GetProfilesByUsernames |  Avg| 18ms| 16ms | -2ms | -10.980
| |  P99| 221ms| 205ms | -16ms | -7.231
| UserStore.GetProfilesInChannel |  Avg| 24ms| 11ms | -13ms | -55.154
| |  P99| 225ms| 92ms | -133ms | -59.243
| UserStore.GetProfilesNotInChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 211ms| 96ms | -115ms | -54.503
| UserStore.GetUnreadCount |  Avg| 14ms| 13ms | -1ms | -7.107
| |  P99| 199ms| 181ms | -18ms | -9.042
| UserStore.IsEmpty |  Avg| 6ms| 5ms | -1ms | -17.345
| |  P99| 79ms| 62ms | -17ms | -21.494
| UserStore.Save |  Avg| 189ms| 184ms | -5ms | -2.639
| |  P99| 800ms| 735ms | -65ms | -8.125
| UserStore.Search |  Avg| 55ms| 52ms | -3ms | -5.445
| |  P99| 249ms| 243ms | -6ms | -2.409
| UserStore.Update |  Avg| 31ms| 30ms | -1ms | -3.215
| |  P99| 282ms| 233ms | -49ms | -17.397
| UserStore.UpdateFailedPasswordAttempts |  Avg| 11ms| 10ms | -1ms | -8.991
| |  P99| 130ms| 97ms | -33ms | -25.470
| UserStore.UpdateLastLogin |  Avg| 10ms| 9ms | -1ms | -10.068
| |  P99| 92ms| 88ms | -4ms | -4.338
| UserStore.UpdateUpdateAt |  Avg| 10ms| 9ms | -1ms | -9.663
| |  P99| 97ms| 88ms | -9ms | -9.323
| UserTermsOfServiceStore.GetByUser |  Avg| 12ms| 10ms | -2ms | -17.177
| |  P99| 173ms| 126ms | -47ms | -27.134
| WebhookStore.GetOutgoingByTeam |  Avg| 21ms| 19ms | -2ms | -9.647
| |  P99| 238ms| 226ms | -12ms | -5.045
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 588ms| 498ms | -90ms | -15.316
| | P99| 3.486s| 2.487s | -999ms | -28.657
| addTeamMember | Avg| 1.624s| 1.43s | -194ms | -11.948
| | P99| 9.763s| 8.73s | -1.033s | -10.581
| autocompleteChannelsForTeamForSearch | Avg| 85ms| 80ms | -5ms | -5.865
| | P99| 528ms| 720ms | 192ms | 36.341
| autocompleteUsers | Avg| 77ms| 72ms | -5ms | -6.494
| | P99| 450ms| 423ms | -27ms | -5.996
| channelMemberCountsByGroup | Avg| 29ms| 0s | -29ms | -100.094
| | P99| 97ms| 0s | -97ms | -99.743
| createCategoryForTeamForUser | Avg| 29ms| 198ms | 169ms | 576.712
| | P99| 98ms| 965ms | 867ms | 889.230
| createChannel | Avg| 446ms| 451ms | 5ms | 1.120
| | P99| 2.305s| 2.125s | -180ms | -7.809
| createChannelBookmark | Avg| 114ms| 42ms | -72ms | -63.351
| | P99| 895ms| 237ms | -658ms | -73.521
| createDirectChannel | Avg| 629ms| 533ms | -96ms | -15.272
| | P99| 3.222s| 2.385s | -837ms | -25.979
| createGroupChannel | Avg| 1.033s| 969ms | -64ms | -6.198
| | P99| 6.25s| 4.8s | -1.45s | -23.199
| createPost | Avg| 824ms| 759ms | -65ms | -7.889
| | P99| 4.929s| 4.678s | -251ms | -5.092
| createSchedulePost | Avg| 24ms| 25ms | 1ms | 4.231
| | P99| 365ms| 231ms | -134ms | -36.711
| createUser | Avg| 460ms| 423ms | -37ms | -8.045
| | P99| 2.415s| 2.343s | -72ms | -2.982
| deleteChannelBookmark | Avg| 28ms| 26ms | -2ms | -7.059
| | P99| 50ms| 50ms | 0s | 0.000
| deleteDraft | Avg| 23ms| 20ms | -3ms | -12.955
| | P99| 245ms| 230ms | -15ms | -6.124
| deletePost | Avg| 106ms| 96ms | -10ms | -9.394
| | P99| 485ms| 486ms | 1ms | 0.206
| followThreadByUser | Avg| 118ms| 75ms | -43ms | -36.487
| | P99| 725ms| 422ms | -303ms | -41.794
| getAllTeams | Avg| 15ms| 13ms | -2ms | -13.336
| | P99| 212ms| 185ms | -27ms | -12.742
| getAnalytics | Avg| 79ms| 0s | -79ms | -100.184
| | P99| 100ms| 0s | -100ms | -100.468
| getCategoriesForTeamForUser | Avg| 23ms| 21ms | -2ms | -8.561
| | P99| 244ms| 230ms | -14ms | -5.740
| getChannel | Avg| 36ms| 31ms | -5ms | -13.929
| | P99| 408ms| 276ms | -132ms | -32.353
| getChannelMember | Avg| 25ms| 22ms | -3ms | -11.901
| | P99| 319ms| 242ms | -77ms | -24.165
| getChannelMembers | Avg| 106ms| 27ms | -79ms | -74.679
| | P99| 940ms| 98ms | -842ms | -89.574
| getChannelMembersForTeamForUser | Avg| 19ms| 17ms | -2ms | -10.355
| | P99| 229ms| 206ms | -23ms | -10.054
| getChannelMembersForUser | Avg| 14ms| 12ms | -2ms | -14.073
| | P99| 189ms| 150ms | -39ms | -20.626
| getChannelStats | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 193ms| 183ms | -10ms | -5.175
| getChannelUnread | Avg| 20ms| 19ms | -1ms | -5.067
| | P99| 239ms| 231ms | -8ms | -3.353
| getChannelsForTeamForUser | Avg| 20ms| 17ms | -3ms | -14.947
| | P99| 234ms| 215ms | -19ms | -8.123
| getChannelsForUser | Avg| 13ms| 11ms | -2ms | -15.843
| | P99| 182ms| 148ms | -34ms | -18.718
| getClientConfig | Avg| 27ms| 23ms | -4ms | -15.027
| | P99| 330ms| 255ms | -75ms | -22.740
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 24ms| 20ms | -4ms | -16.543
| | P99| 249ms| 229ms | -20ms | -8.041
| getFilePreview | Avg| 81ms| 77ms | -4ms | -4.950
| | P99| 475ms| 456ms | -19ms | -4.000
| getFileThumbnail | Avg| 70ms| 66ms | -4ms | -5.751
| | P99| 446ms| 421ms | -25ms | -5.609
| getFilteredUsersStats | Avg| 16ms| 0s | -16ms | -100.497
| | P99| 25ms| 0s | -25ms | -100.604
| getJobsByType | Avg| 29ms| 0s | -29ms | -100.144
| | P99| 97ms| 0s | -97ms | -99.488
| getPostThread | Avg| 92ms| 82ms | -10ms | -10.854
| | P99| 917ms| 785ms | -132ms | -14.396
| getPostsForChannel | Avg| 167ms| 146ms | -21ms | -12.548
| | P99| 2.23s| 1.991s | -239ms | -10.716
| getPostsForChannelAroundLastUnread | Avg| 65ms| 57ms | -8ms | -12.313
| | P99| 734ms| 497ms | -237ms | -32.308
| getPreferences | Avg| 15ms| 13ms | -2ms | -13.321
| | P99| 207ms| 176ms | -31ms | -14.990
| getPrevTrialLicense | Avg| 7ms| 0s | -7ms | -107.143
| | P99| 25ms| 0s | -25ms | -101.833
| getProfileImage | Avg| 81ms| 77ms | -4ms | -4.949
| | P99| 491ms| 479ms | -12ms | -2.444
| getPublicChannelsForTeam | Avg| 35ms| 32ms | -3ms | -8.656
| | P99| 234ms| 233ms | -1ms | -0.428
| getRolesByNames | Avg| 21ms| 0s | -21ms | -100.011
| | P99| 49ms| 0s | -49ms | -99.492
| getServerLimits | Avg| 26ms| 0s | -26ms | -98.235
| | P99| 50ms| 0s | -50ms | -100.503
| getTeamMember | Avg| 14ms| 12ms | -2ms | -14.231
| | P99| 191ms| 161ms | -30ms | -15.671
| getTeamMembersForUser | Avg| 14ms| 12ms | -2ms | -14.130
| | P99| 204ms| 175ms | -29ms | -14.220
| getTeamScheduledPosts | Avg| 23ms| 20ms | -3ms | -13.064
| | P99| 246ms| 226ms | -20ms | -8.115
| getTeamStats | Avg| 84ms| 77ms | -7ms | -8.289
| | P99| 245ms| 244ms | -1ms | -0.408
| getTeamsForUser | Avg| 13ms| 11ms | -2ms | -15.154
| | P99| 190ms| 149ms | -41ms | -21.525
| getTeamsUnreadForUser | Avg| 25ms| 21ms | -4ms | -16.114
| | P99| 285ms| 238ms | -47ms | -16.463
| getThreadsForUser | Avg| 22ms| 19ms | -3ms | -13.383
| | P99| 241ms| 224ms | -17ms | -7.056
| getUser | Avg| 24ms| 20ms | -4ms | -16.578
| | P99| 366ms| 259ms | -107ms | -29.267
| getUserByUsername | Avg| 2ms| 0s | -2ms | -89.791
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 1ms| 0s | -1ms | -189.485
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 5ms| 4ms | -1ms | -20.178
| | P99| 138ms| 98ms | -40ms | -29.034
| getUsers | Avg| 21ms| 18ms | -3ms | -14.066
| | P99| 343ms| 249ms | -94ms | -27.377
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 73ms| 61ms | -12ms | -16.524
| getUsersByNames | Avg| 19ms| 17ms | -2ms | -10.482
| | P99| 227ms| 212ms | -15ms | -6.614
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 130ms| 0s | -130ms | -99.625
| | P99| 247ms| 0s | -247ms | -99.999
| listCPAFields | Avg| 13ms| 12ms | -1ms | -7.485
| | P99| 198ms| 181ms | -17ms | -8.606
| listCPAValues | Avg| 21ms| 17ms | -4ms | -19.300
| | P99| 234ms| 209ms | -25ms | -10.697
| listChannelBookmarksForChannel | Avg| 15ms| 14ms | -1ms | -6.584
| | P99| 214ms| 196ms | -18ms | -8.401
| login | Avg| 247ms| 235ms | -12ms | -4.864
| | P99| 2.237s| 2.227s | -10ms | -0.447
| logout | Avg| 150ms| 119ms | -31ms | -20.686
| | P99| 690ms| 476ms | -214ms | -31.015
| patchPost | Avg| 126ms| 103ms | -23ms | -18.235
| | P99| 1.1s| 812ms | -288ms | -26.183
| removeUserCustomStatus | Avg| 365ms| 354ms | -11ms | -3.012
| | P99| 2.011s| 2.011s | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 55ms| 48ms | -7ms | -12.622
| | P99| 499ms| 453ms | -46ms | -9.220
| searchAllChannels | Avg| 58ms| 54ms | -4ms | -6.880
| | P99| 322ms| 246ms | -76ms | -23.599
| searchGroupChannels | Avg| 23ms| 19ms | -4ms | -17.057
| | P99| 241ms| 218ms | -23ms | -9.545
| searchPostsInTeam | Avg| 242ms| 218ms | -24ms | -9.930
| | P99| 2.456s| 2.344s | -112ms | -4.560
| searchUsers | Avg| 58ms| 54ms | -4ms | -6.945
| | P99| 282ms| 246ms | -36ms | -12.783
| setPostReminder | Avg| 99ms| 74ms | -25ms | -25.192
| | P99| 858ms| 460ms | -398ms | -46.414
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 75ms| 57ms | -18ms | -24.093
| | P99| 639ms| 488ms | -151ms | -23.641
| updateCategoriesForTeamForUser | Avg| 249ms| 188ms | -61ms | -24.469
| | P99| 2.85s| 2.043s | -807ms | -28.317
| updateChannelBookmark | Avg| 24ms| 27ms | 3ms | 12.602
| | P99| 50ms| 239ms | 189ms | 381.080
| updateChannelBookmarkSortOrder | Avg| 58ms| 65ms | 7ms | 12.146
| | P99| 243ms| 247ms | 4ms | 1.649
| updatePreferences | Avg| 51ms| 43ms | -8ms | -15.797
| | P99| 467ms| 437ms | -30ms | -6.426
| updateReadStateAllThreadsByUser | Avg| 72ms| 8ms | -64ms | -88.343
| | P99| 243ms| 48ms | -195ms | -80.164
| updateReadStateThreadByUser | Avg| 185ms| 169ms | -16ms | -8.658
| | P99| 1.852s| 1.501s | -351ms | -18.955
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 569ms| 561ms | -8ms | -1.407
| | P99| 2.324s| 2.321s | -3ms | -0.129
| upsertDraft | Avg| 23ms| 21ms | -2ms | -8.560
| | P99| 239ms| 226ms | -13ms | -5.436
| viewChannel | Avg| 64ms| 57ms | -7ms | -10.905
| | P99| 724ms| 545ms | -179ms | -24.717
